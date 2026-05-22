<h1>OSINT Exercise #006 — Media Misattribution Investigation - Gralhix - by Sofia Santos
</h1>
<a href="https://gralhix.com/list-of-osint-exercises/osint-exercise-006/">Source</a>

<img src="https://gralhix.com/wp-content/uploads/2023/08/osintexercise006.webp" />

<h2>Objective</h2>
<p>Verify that the image used in the tweet is not of the event described. </p>

<h2>Skills Practiced</h2>
<ul style="list-style-type: '- '; padding-left: 20px;">
  <li>Reverse image search and source tracing</li>
  <li>Cross-referencing multiple sources for verification</li>
  <li>Identifying media misattribution and disinformation patterns</li>
  <li>Geopolitical incident verification using open-source databases</li>
</ul>

<h2>Tools Used</h2>
<ul style="list-style-type: '- '; padding-left: 20px;">
  <li>South Asia Terrorism Portal (SATP) — Fact-checking incident dates and casualties in the Khyber Pakhtunkhwa region.</li>
  <li>TinEye — Reverse image search used to establish the earliest indexed appearance of the media.</li>
  <li>Alamy Imagery Archive — Cross-referencing commercial stock metadata against official records.</li>
  <li>Visual Information Record Identification Number (VIRIN) Analysis — Decoding military metadata to verify capture dates and locations. (VIRIN)</li>
</ul>

<h2>Process</h2>

<h3>Step 1 — Identifying the Media Source</h3>

<img width="654" height="257" alt="595056524-b1f9bc65-ded2-4525-a8d8-9eb688fafbdc" src="https://github.com/user-attachments/assets/e8f704b3-f183-484f-83bf-6e410e4997f8" />

<i>Ref 1: Google Lens result showing Baghdad bombing context</i>

<p>The search flagged the image as related to a bombing in Baghdad, 
Iraq, <b>2006</b> and noted its prior misuse on social media for unrelated events, including attacks in Pakistan.<br><br>
As it was just an overview so nothing can be concluded from this search alone.</p>

<h3>Step 2 — Establishing the Original Date: The "VIRIN" Discovery</h3>

<img width="676" height="258" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/91e77aa5-9648-46ee-8912-a355b5fe26e2" />

<img width="690" height="269" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/fe41f9f0-55ba-4298-b2d7-189b54691e18" />

<i>Ref 2: Google Search results showing April 14, 2005</i>

<p>I identified the official U.S. Military VIRIN (050414-A-3240S-026) associated with the photo. I decoded the first six digits (050414) which follow the standard YYMMDD format, confirming the image was captured on April 14, 2005. This technical metadata immediately provided irrefutable proof that the image predates the 2023 Pakistan incident by 18 years. <br><br>U.S. military metadata confirms the image 
was captured live by <b>Spc. Ronald Shaw Jr.</b> on <b>April 14, 2005</b>.<br><br>

<h3>Step 2.1 — Verification of Discrepancies: Resolving the Conflict</h3>
<br>
<p>During verification, I encountered a discrepancy where an Alamy archive listed the capture date as August 28, 2006. By cross-referencing this against the official Army VIRIN and the photographer's credit (Spc. Ronald Shaw Jr.), I determined the 2006 date was an archival entry error. This step was vital to ensure the highest level of evidentiary accuracy."
</p><br>

<h3>Step 3 — TinEye</h3>
<p>Then I used TinEye (TinEye is a reverse image search engine that lets you find the original source of an image,
track where it appears online, and discover if it has been altered or stolen) for a reverse image search.</p>

<img width="825" height="488" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/aed1c546-7993-4b4a-a995-7009a9d65461" />

<i>Ref 3: TinEye results showing Alamy as the first indexed result</i>

<p>The earliest indexed appearance pointed to an Alamy stock listing(Alamy is a massive online content marketplace and
stock photography agency)  dated <b>Dec 6, 2023</b> — likely the upload date, not the capture date.</p>

<img width="801" height="497" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/1951a3a3-e343-4e36-ad60-1ba513c62ba2" />

<i>Ref 3.1: Alamy Webpage showing the capture date of the image</i>

<p>After clicking on it, it revealed the Date of Capture,i.e., <b>28 August 2006</b>(earlier than the tweet but still post-dating the confirmed 2005 capture), 
which further verified that the tweet image is the wrong one.</p>

<h3>Step 4 — Verifying the Pakistan Incident (SATP Database)</h3>

<img width="1124" height="369" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/23540144-b3f5-4c0d-946b-7b03930b2593" />

<img width="661" height="224" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/c5cf6203-729b-46b2-9308-b4de477d10ee" />

<i>Ref 4: SATP database confirming the January 19, 2023 TTP attack</i>

<p>To determine if the tweet was entirely fabricated or just misillustrated, I used the South Asia Terrorism Portal (SATP). I confirmed that a TTP attack did occur on January 19, 2023, resulting in the deaths of three police constables</p>

<h2>Findings</h2>
<ul style="list-style-type: '- '; padding-left: 20px;">
  <li>The image does not depict the Pakistan attack.</li>
  <li>It originates from a car bombing in Baghdad, Iraq, on April 14, 2005.</li>
  <li>The tweet's text was accurate but illustrated with an unrelated image.</li>
  <li>This is a case of <strong>media misattribution</strong> — a common disinformation pattern.</li>
</ul><br>

<h2>Conclusion</h2>
<br>
<p>This is a case of Media Misattribution. The text of the tweet was factually accurate, but the user used an unrelated, high-impact photo from the Iraq War to increase engagement or sensationalise the event</p> <br>                                                               

<h2>References</h2>
<ol>
  <li><a href="https://he.wiktionary.org/wiki/%D7%A7%D7%95%D7%91%D7%A5:Car_bomb_in_Iraq.jpg">Image source — Wikimedia/Wiktionary</a></li>
  <li><a href="https://www.satp.org/terrorism-assessment/pakistan-khyberpakhtunkhwa-2023">SATP — Pakistan Khyber Pakhtunkhwa 2023</a></li>
</ol>
