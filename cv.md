# ANASTASIIA VEROIVSKA
Email: veroivska@gmail.com +380688314838

I'm an enthusiastic and detail-oriented Frontend Software
Engineer seeking an entry-level position with Company to
use my skills in coding, troubleshooting complex problems,
and assisting in the timely completion of projects.

## Skills
* Html/Css
* Bootstrap
* Sass/Scss
* JavaScript
* Gulp

#### Get the keyCode
```
const insert = document.getElementById('insert')

window.addEventListener('keydown', (event) => {
  insert.innerHTML = `
  <div class="key">
  ${event.key === ' ' ? 'Space' : event.key} 
  <small>event.key</small>
</div>
<div class="key">
  ${event.keyCode}
  <small>event.keyCode</small>
</div>
<div class="key">
  ${event.code}
  <small>event.code</small>
</div>
})
```
