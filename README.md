<!-- # 👋 Halo, saya Rafif Fadhil Dharmawan -->
<div class="logo-container">
<div class="red circle"></div>
<div class="yellow circle"></div>
<div class="green circle"></div>
</div>
<h2 style="color: black;">tes</h2>
<div class="main-name">
            <h1>Rafif Fadhil Dharmawan</h1>
            <p>Frontend Developer | Web Enthusiast</p>
    </div>
<!--
**RafalDigital/RafalDigital** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div class="main-button">
<button>Lets See</button>
</div>

<style>
    :root {
  --primary: #1d1e22;
  --secondary: #22232e;
  --option1: #26272d;
  --option2: #2f3137;
  --option3: #2a2b3e;
  --option4: #22232e;
  --red: #ff5d56;
  --yellow: #fcba2b;
  --green: #28c73f;
  --white: #ffffff;
  --gray: #a0a0a0;
}


    .logo-container {
        display: flex;
        justify-content: center;
        margin-bottom: 2em;
    }

    .logo-container .circle {
        width: 10px; height: 10px;
        border-radius: 100%;
        margin-right: 10px;
    }

    .red{background-color: #ff5d56; animation: animasiLogo 1s ease infinite;}
    .yellow{background-color: #fcba2b; animation: animasiLogo 1s ease infinite; animation-delay: .3s;}
    .green{background-color: #28c73f; animation: animasiLogo 1s ease infinite; animation-delay: .6s;}

    @keyframes animasiLogo{
         0%{
            transform: translateY(0px);
        }
        50% {
            transform: translateY(12px);
        }
        100%{
            transform: translateY(0px);
        }
    }

    .main-name {
        text-align: center;
        z-index: 1;
        position: relative;
        padding: 0 20px;
        margin-top: 5rem;
        margin-bottom: 5rem;
    }

    .main-name h1 {
        font-size: 1.5rem;
        font-weight: 700;
        margin-bottom: 0;
        background: linear-gradient(135deg, #fcba2b, #ff5d56);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    .main-name p {
        margin-top: 0;
        font-size: .8rem;
        color: var(--white);
        margin-bottom: 30px;
    }

    .main-button {
        text-align: center;
    }
    .main-button button {
        border: none;
        display: inline-flex;
        align-items: center;
        gap: 10px;
        padding: 15px 40px;
        background: linear-gradient(135deg, #fcba2b, #ff5d56);
        font-weight: bold;
        color: var(--white);
        text-decoration: none;
        border-radius: 50px;
        font-weight: 600;
        transition: transform 0.3s, box-shadow 0.3s;
    }

    .main-button button:hover {
        transform: translateY(-2px);
        box-shadow: 0 5px 20px rgba(252, 186, 43, 0.4);
    }
</style>
