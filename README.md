# Derm Assist

Derm Assist is a Flask + SQLite skincare assistant with registration, login, AI-style image scan analysis, scan history, product suggestions, cart checkout, and a Capacitor Android wrapper.

## Web App Setup

Install Python 3.10 or newer, then run:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
py app.py
```

Open:

```text
http://127.0.0.1:5000
```

The app serves the HTML screens and API from the same Flask server, so old ngrok URLs are not needed for local use.

## Android Sync

After editing any web files, sync them into the Android project:

```powershell
npm run android:sync
```

Then open Android Studio:

```powershell
npm run android:open
```

## Main Files

- `app.py` - Flask API, SQLite tables, image upload, scan analysis, profile and history routes.
- `*.html` - Web screens used by the Flask app.
- `www/` - Synced web assets for Capacitor.
- `android/` - Capacitor Android project.

  <img width="2880" height="1800" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/1b2a773c-1f2e-44d1-babd-ae81eba392e1" />
<img width="2880" height="1800" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/2561bb8b-4067-4dc3-8239-2244afb08ad3" />
<img width="2880" height="1800" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/7480bdf1-4bac-4883-92c7-1c01a8965177" />
<img width="2880" height="1800" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/58db66a4-e198-436e-a5b8-854faf704863" />
<img width="2880" height="1800" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/7d5e77c2-7e57-43d8-aa7f-6f76616d9462" />
<img width="2880" height="1800" alt="Screenshot (257)" src="https://github.com/user-attachments/assets/829f87f4-623a-4e1e-a41b-ded852e57e24" />
<img width="2880" height="1800" alt="Screenshot (256)" src="https://github.com/user-attachments/assets/3c906ed5-6d4f-4e01-87a1-8100d0885c97" />
<img width="2880" height="1800" alt="Screenshot (259)" src="https://github.com/user-attachments/assets/cc4602da-d45f-4e65-98cd-6d9c1b8c808d" />
<img width="2880" height="1800" alt="Screenshot (258)" src="https://github.com/user-attachments/assets/c58878c9-ddd9-46cf-8f02-a03985382310" />
<img width="2880" height="1800" alt="Screenshot (262)" src="https://github.com/user-attachments/assets/f7c37a05-f94a-4e8c-8889-bc2c289ca8bf" />
<img width="2880" height="1800" alt="Screenshot (261)" src="https://github.com/user-attachments/assets/2dd50cd7-18dc-45d5-bf81-f20c938e629f" />
<img width="2880" height="1800" alt="Screenshot (260)" src="https://github.com/user-attachments/assets/b17d1b6f-680d-491e-8fd2-d665be3e1459" />
<img width="2880" height="1800" alt="Screenshot (270)" src="https://github.com/user-attachments/assets/2b18de4a-c320-49bd-839e-af4ddf704e40" />
<img width="2880" height="1800" alt="Screenshot (269)" src="https://github.com/user-attachments/assets/d4cb139f-cf11-4d76-ab61-46825e3e1fb9" />
<img width="2880" height="1800" alt="Screenshot (268)" src="https://github.com/user-attachments/assets/76f647b3-eadc-410f-b77c-3067154f9432" />
<img width="2880" height="1800" alt="Screenshot (267)" src="https://github.com/user-attachments/assets/091d6206-9e7c-4609-a4ec-19052cb22065" />
<img width="2880" height="1800" alt="Screenshot (266)" src="https://github.com/user-attachments/assets/e2aaf12c-6234-4ae0-8953-b857d29decf8" />
<img width="2880" height="1800" alt="Screenshot (265)" src="https://github.com/user-attachments/assets/c2ceb3e8-856d-4956-9076-c14ba2eb3945" />
<img width="2880" height="1800" alt="Screenshot (264)" src="https://github.com/user-attachments/assets/c182ea02-5fdd-425a-8679-dfdc60487748" />
<img width="2880" height="1800" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/bd43e4c7-8af5-498c-ab37-a3246f814d65" />
<img width="2880" height="1800" alt="Screenshot (272)" src="https://github.com/user-attachments/assets/f879950e-b440-4a2e-815f-7ab57647ba46" />
<img width="2880" height="1800" alt="Screenshot (271)" src="https://github.com/user-attachments/assets/94cb5acd-c33d-4e48-a79f-f1a3b99ca3d7" />
<img width="2880" height="1800" alt="Screenshot (275)" src="https://github.com/user-attachments/assets/5396884c-8226-40cd-bfa6-265a0a13c627" />
<img width="2880" height="1800" alt="Screenshot (274)" src="https://github.com/user-attachments/assets/104ba2b4-d5fe-437e-b333-5c54bf467f07" />
<img width="2880" height="1800" alt="Screenshot (273)" src="https://github.com/user-attachments/assets/1cdcfd17-8f22-4b17-ab24-4d6fa7c937e4" />
<img width="2880" height="1800" alt="Screenshot (278)" src="https://github.com/user-attachments/assets/be761138-67f4-4f9b-8e47-44d40c464996" />
<img width="2880" height="1800" alt="Screenshot (277)" src="https://github.com/user-attachments/assets/9b4bb63d-94c1-45f3-8e04-74298258738b" />
<img width="2880" height="1800" alt="Screenshot (276)" src="https://github.com/user-attachments/assets/258e7698-75f5-4bda-96c5-33eb19972e43" />
<img width="2880" height="1800" alt="Screenshot (280)" src="https://github.com/user-attachments/assets/81b03f1e-dd6d-48d4-9c5f-b57c390383e7" />
<img width="2880" height="1800" alt="Screenshot (282)" src="https://github.com/user-attachments/assets/cf252bcb-3e75-4d91-bdcd-0f1275f8899d" />
<img width="2880" height="1800" alt="Screenshot (281)" src="https://github.com/user-attachments/assets/fda6fa50-bba4-4a74-9c45-0efe69f06ac4" />
<img width="2880" height="1800" alt="Screenshot (284)" src="https://github.com/user-attachments/assets/23e042db-1fdb-47a1-bdf9-5783499bf62e" />
<img width="2880" height="1800" alt="Screenshot (283)" src="https://github.com/user-attachments/assets/e15648fc-d415-4251-9d66-9cdf267af7a2" />
