<style>
body{
	height 100vh
	width 100vw
	background transparent radial-gradient(at calc(var(--mouse-x, 0) * 100%) calc(var(--mouse-y, 0) * 100%), yellow, green) no-repeat 0 0
	}
</style

<div id="header" align="center">
	<img src="https://media.giphy.com/media/Dh5q0sShxgp13DwrvG/giphy.gif" width="200" />
	<h1 align="center">Hola mundo 👋 </h1>
	<h3 align="center">Próximamente... </h3>
</div>
<body>
<!--
**rodrigopradoc/rodrigopradoc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:-->
---

## 🤔 Sobre mí:
<!--- 🔭 I’m currently working on ...-->
- 🌱 Actualmente estoy aprendiendo TypeScript, React y Next.js
<!--- 👯 I’m looking to collaborate on ...-->
<!--- 🤔 I’m looking for help with ...-->
<!--- 💬 Ask me about ...-->
- 📫 Mi correo personal es: rodrigo070998.2@gmail.com
<!--- 😄 Pronouns: ...-->
<!--- ⚡ Fun fact: ...-->
</body>
<script>
const root = document.documentElement;
 
document.addEventListener('mousemove', evt => {
    let x = evt.clientX / innerWidth;
    let y = evt.clientY / innerHeight;
 
    root.style.setProperty('--mouse-x', x);
    root.style.setProperty('--mouse-y', y);
});
</script>
