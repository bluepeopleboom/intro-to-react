# Styling and CSS

โดยปกติแล้ว React สามารถที่จะเขียน CSS ได้ด้วยการสร้างไฟล์ `.css` มาจากนั้นก็ให้ import เข้ามาในไฟล์ที่เราต้องการใช้ CSS Classes นั้น ๆ

ในไฟล์ App.js เราจะ import ไฟล์ CSS ที่เกี่ยวข้องเข้ามา

```js
import "./App.css";

function App() {
  return (
    <div className="postapp-header">
      <h1>Post App</h1>
      <button className="postapp-header-add-button">Add Post</button>
    </div>
  );
}
```

ภายใน App.css เราจะเขียน CSS ปกติ

```css
.postapp-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px 15px;
  background-color: bisque;
}

.postapp-header-add-button {
  height: 40px;
}
```

<br><hr><br>

## Inline Styling

เราสามารถที่จะเขียน css แบบ inline ได้

⚠️ แต่ว่า inline style นั้นจะเขียนอยู่ในรูปแบบของ Object CSS properties จะต่างจากปกติ

```js
function App() {
  return (
    <div style={{
      display: "flex";
      justifyContent: "space-between";
      alignItems: "center";
      padding: "0px 15px";
      backgroundColor: "bisque";
    }}>
      <h1>Post App</h1>
      <button style={{
        height: "40px";
      }}>Add Post</button>
    </div>
  );
}
```

<br><hr><br>

## CSS IN JS

CSS In JS เป็น concept ที่เขียน CSS ด้วย JS ทำให้เราสามารถที่จะเขียน logic ที่มีความซับซ้อน CSS ของเราได้อย่างยืดหยุ่น เราจะแนะนำเครื่องมือที่ช่วยในการเขียน CSS ของเราด้วย concept ของ CSS in JS ก็คือ **"Emotion"**

<br><hr><br>

## Emotion

TBD

<br><hr><br>

[Table of Contents](https://github.com/napatwongchr/intro-to-react/blob/main/README.md)
