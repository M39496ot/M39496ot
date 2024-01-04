from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def index():
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تطبيق القرآن الكريم</title>
</head>
<body>
    <h1>مرحبًا بك في تطبيق القرآن الكريم</h1>
    <!-- أضف أي عناصر HTML إضافية هنا -->
</body>
</html>
=== compile output ===

main.cpp:1:1: error: unknown type name 'from'
from flask import Flask, render_template
^
main.cpp:1:11: error: expected ';' after top level declarator
from flask import Flask, render_template
          ^
          ;
2 errors generated.

