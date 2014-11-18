# talks

![block talks](https://1.downloader.disk.yandex.ru/preview/4dfaaecbdd6d98316b8761da1f3aab86/mpfs/iSPSeRBLlnT17lVa2O_VvQncFg28G6ln2OCxDOn_9xkdTre6jHpcip0Ro3qX5yugnwcddOzvxm4Q8BHce2XwLg%3D%3D?uid=0&filename=talkspng&disposition=inline&hash=&limit=0&content_type=image%2Fpng&size=XXL&crop=0)

```javascript
{
    block : 'talks',
    slides : 'url',
    audio : 'url',
    index : [
        { 'Приветствие' : 0 },
        { 'Обзор выступления' : 120 },
        { 'Тема 1' : 1120 },
        { 'Тема 2' : 2120 },
        { 'Вопросы' : 1050 }
    ]
}
```

Основная задача: проигрывать запись выступления, синхронно отображая слайды презентации.

Блок должен уметь:

- отображать презентации с сервисов (например slideshare), если это будет возможным.
- отображать между слайдами произвольное изображение или кусок отформатированного кода (мастер-класс)
