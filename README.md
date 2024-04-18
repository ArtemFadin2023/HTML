from django.http import HttpResponse

def check_number(request, num):
    num = int(num)
    is_even = num % 2 == 0
    ends_with_7 = num % 10 == 7
    return HttpResponse({
        'is_even': is_even,
        'ends_with_7': ends_with_7
    })

from django.http import HttpResponse

def next_even(request, n):
    n = int(n)
    next_even = n + 2 if n % 2 == 0 else n + 1
    return HttpResponse(f"Следующее Число {n} это {next_even}.")
