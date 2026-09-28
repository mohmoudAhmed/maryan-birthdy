HAPPY BIRTHDAY PROJECT
======================
Faylasha:
  index.html      -> website-ka oo dhan
  photos/         -> sawirradaada (1.jpg ... 6.jpg)
  music/          -> birthday.mp3 (ikhtiyaari)

Beddel magaca / qoraalka (kor u fur index.html, qaybta <script>):
  const TITLE='Happy Birthday Anita 🤎';
  const INTRO='HAPPY|BIRTHDAY|Anita 💖';

Tijaabi local (ka dooro mid):
  python -m http.server 8000     -> fur http://localhost:8000
  (ama double-click index.html)

Ku soo rar GitHub Pages:
  git init
  git add .
  git commit -m "birthday"
  git branch -M main
  git remote add origin https://github.com/USERNAME/birthday.git
  git push -u origin main
  Kadib: Settings -> Pages -> main / (root) -> Save
  Link: https://USERNAME.github.io/birthday/
