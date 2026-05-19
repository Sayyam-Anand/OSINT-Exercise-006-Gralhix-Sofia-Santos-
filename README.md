<h1>OSINT Exercise #006 — Media Misattribution Investigation - Gralhix - by Sofia Santos
</h1>
<a href="https://gralhix.com/list-of-osint-exercises/osint-exercise-006/">Source</a>

<img src="https://gralhix.com/wp-content/uploads/2023/08/osintexercise006.webp" />

<h2>Objective</h2>
<p>Verify whether the image used in a tweet about a TTP attack in 
Khyber, Pakistan actually depicts the event described, using 
reverse image search and open-source verification methods. </p>

<h2>Skills Practiced</h2>
<ul style="list-style-type: '- '; padding-left: 20px;">
  <li>Reverse image search and source tracing</li>
  <li>Cross-referencing multiple sources for verification</li>
  <li>Identifying media misattribution and disinformation patterns</li>
  <li>Geopolitical incident verification using open-source databases</li>
</ul>

<h2>Tools Used</h2>
<ul style="list-style-type: '- '; padding-left: 20px;">
  <li>Google Lens — initial reverse image search and AI overview</li>
  <li>Google AI Mode Search — date verification and incident confirmation</li>
  <li>TinEye — tracing earliest online appearances of the image</li>
  <li>Alamy — stock image metadata and date reference</li>
</ul>

<h2>Process</h2>

<h3>Step 1 — Google Lens</h3>

<img width="700" height="350" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/b1f9bc65-ded2-4525-a8d8-9eb688fafbdc" />

<i>Ref 1: Google Lens result showing Baghdad bombing context</i>

The AI overview flagged the image as related to a bombing in Baghdad, 
Iraq, <b>2006</b> and noted its prior misuse on social media for unrelated events, including attacks in Pakistan.
As It was just an overveiw so nohting can be concluded from this search alone.

<h3>Step 2 — Establishing the Original Date</h3>

<img width="676" height="258" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/91e77aa5-9648-46ee-8912-a355b5fe26e2" />

<img width="690" height="269" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/fe41f9f0-55ba-4298-b2d7-189b54691e18" />

<i>Ref 2: Google AI Mode Search results showing April 14, 2005</i>

The original date of the bombing in Baghdad, Iraq is <b>April 14, 2005</b>.
U.S. military metadata (VIRIN: 050414-A-3240S-026) confirms the image 
was captured live by <b>Spc. Ronald Shaw Jr.</b>. on <b>April 14, 2005</b>. An earlier 
2006 reference was a mislabeling error in archival records.

This shows that the tweet image may be the incorrect image of the depicted event.

<h3>Step 3 — TinEye</h3>
Then I used TinEye (TinEye is a reverse image search engine that lets you find the original source of an image,
track where it appears online, and discover if it has been altered or stolen) for a reverse image search.

<img width="825" height="488" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/aed1c546-7993-4b4a-a995-7009a9d65461" />

<i>Ref 3: TinEye results showing Alamy as the first indexed result</i>

The earliest indexed appearance pointed to an Alamy stock listing(Alamy is a massive online content marketplace and
stock photography agency)  dated <b>Dec 6, 2023</b> — likely the upload date, not the capture date.

<img width="801" height="497" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/1951a3a3-e343-4e36-ad60-1ba513c62ba2" />

<i>Ref 3.1: Alamy Webpage showig the capture date of the image</i>

After clicking on it, it revealed the Date of Capture,i.e., <b>28 August 2006</b>(although not exactly the correct date), 
which further verified that the tweet image is the wrong one.

<h3>Step 4 — Verifying the Pakistan Incident</h3>

<img width="1124" height="369" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/23540144-b3f5-4c0d-946b-7b03930b2593" />

<img width="661" height="224" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/c5cf6203-729b-46b2-9308-b4de477d10ee" />

<i>Ref 4: SATP database confirming the January 19, 2023 TTP attack</i>

Using the AI mode again I found that the attack did occur on <b>January 19, 2023</b>, and did kill three Pakistani 
police constables — the tweet's text was accurate, only the image was wrong.

<h2>Findings</h2>
<ul style="list-style-type: '- '; padding-left: 20px;">
  <li>The image does not depict the Pakistan attack.</li>
  <li>It originates from a car bombing in Baghdad, Iraq, on April 14, 2005.</li>
  <li>The tweet's text was accurate but illustrated with an unrelated image.</li>
  <li>This is a case of <strong>media misattribution</strong> — a common disinformation pattern.</li>
</ul>

<h2>References</h2>
1. [Image source — Wikimedia/Wiktionary](https://he.wiktionary.org/wiki/%D7%A7%D7%95%D7%91%D7%A5:Car_bomb_in_Iraq.jpg)
2. [SATP — Pakistan Khyber Pakhtunkhwa 2023](https://www.satp.org/terrorism-assessment/pakistan-khyberpakhtunkhwa-2023)
