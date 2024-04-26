<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>ArtemFadin</title>
</head>
<body>
    {% block content %}
    <p>Телефон: +79262119421</p>
    <p>Email: artemfadinvip@gmail.com</p>
    {% endblock content %}
    def index(request):
        return render(request, 'index.html')
    def contact(request):
        return render(request, 'contact.html')
</body>
</html>
