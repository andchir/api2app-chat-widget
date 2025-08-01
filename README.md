# api2app-chat-widget
Widget for embedding iframe applications on a website.


```html
<script src="api2app-chat-widget.js"></script>
<script>
    const chatWidget = new Api2AppChatWidget(
        'https://api2app.org/ru/apps/embed/your-app-embed-id', {
            buttonColor: '#007bff',
            hoverColor: '#0056b3',
            position: 'bottom-right',
            width: 350,
            height: 465
        });
</script>
```
![Screenshot](https://github.com/andchir/api2app-chat-widget/blob/main/screenshot.jpg?raw=true)
