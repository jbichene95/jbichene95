### ABOUT ME
<html>
 
 <head>
 <style>
  body {
    display:grid;
    grid-template-rows: 1fr 10rem auto;
    grid-template-areas:"main" "." "footer";
    overflow-x:hidden;
    background:#F5F7FA;
    min-height:100vh;
    font-family: 'Open Sans', sans-serif;
    .footer {
        z-index: 1;
        --footer-background:#ED5565;
        display:grid;
        position: relative;
        grid-area: footer;
        min-height:12rem;
        .bubbles {
            position: absolute;
            top:0;
            left:0;
            right:0;
            height:1rem;
            background:var(--footer-background);
            filter:url("#blob");
            .bubble {
                position: absolute;
                left:var(--position, 50%);
                background:var(--footer-background);
                border-radius:100%;
                animation:bubble-size var(--time, 4s) ease-in infinite var(--delay, 0s),
                    bubble-move var(--time, 4s) ease-in infinite var(--delay, 0s);
                transform:translate(-50%, 100%);
            }
        }
        .content {
            z-index: 2;
            display:grid;
            grid-template-columns: 1fr auto;
            grid-gap: 4rem;
            padding:2rem;
            background:var(--footer-background);
            a, p {
                color:#F5F7FA;
                text-decoration:none;
            }
            b {
                color:white;
            }
            p {
                margin:0;
                font-size:.75rem;
            }
            >div {
                display:flex;
                flex-direction:column;
                justify-content: center;
                >div {
                    margin:0.25rem 0;
                    >* {
                        margin-right:.5rem;
                    }
                }
                .image {
                    align-self: center;
                    width:4rem;
                    height:4rem;
                    margin:0.25rem 0;
                    background-size: cover;
                    background-position: center;
                }
            }
        }
    }
}

@keyframes bubble-size {
    0%, 75% {
        width:var(--size, 4rem);
        height:var(--size, 4rem);
    }
    100% {
        width:0rem;
        height:0rem;
    }
}
@keyframes bubble-move {
    0% {
        bottom:-4rem;
    }
    100% {
        bottom:var(--distance, 10rem);
    }
}

  </style>
 </head>
 <h1> I am a computer engineer that is really passionate about working on </h1>
</html>
<!--
**jbichene95/jbichene95** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
