RAKHSETU DEMO PROTOTYPE
=======================

WHAT'S INCLUDED
- Responsive single-page web prototype
- RakhtVani, RakhtPulse, RakhtMitra and SmartMatch feature sections
- Sample donor search (blood group + city filters)
- Request blood / become a donor demo forms
- Fictional sample data only; no backend, database, SMS, calling, maps or real donor contact

RUN LOCALLY (Mac)
1. Unzip rakhsetu_demo.zip.
2. Open Terminal.
3. Move into the project folder, for example:
   cd ~/Downloads/rakhsetu_demo
   (Use the actual folder location where you extracted it.)
4. Start a local server:
   python3 -m http.server 8000
5. Open this in your browser:
   http://localhost:8000

STOP SERVER
- Return to Terminal and press Control + C.

ALTERNATIVE
- Open index.html directly in your browser. The local server method is recommended.

CUSTOMIZE
- Edit index.html in VS Code.
- Demo donor records are in the `donors` array near the bottom of the file.
- Search filters and form interactions are implemented in the script section.

IMPORTANT
This is a front-end demonstration, not a live blood donation service. Donor profiles and metrics are fictional.
Do not use it to make medical or emergency decisions. A real product needs verified donor consent,
eligibility workflows, secure backend storage, authentication, privacy controls and reliable contact integrations.
