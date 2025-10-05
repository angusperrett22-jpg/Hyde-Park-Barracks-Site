<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Hyde Park Barracks: Exploring Colonial Sydney</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root {
      --ink:#333;
      --bg:#f9f9f9;
      --accent:#00aaff;
      --brick:#8C4A3B;
      --parchment:#fdf6e3;
      --parchment-border:#c58b37;
      --guide-bg:#eef6ff;
      --guide-border:#0077cc;
    }
    * { box-sizing: border-box; }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: var(--bg);
      color: var(--ink);
    }

    /* Hero */
    header {
      background: url('barracksfrontview.jpg') no-repeat center/cover;
      color: #fff;
      text-align: center;
      padding: 80px 20px;
    }
    header h1 { font-size: 2.5em; margin: 0; text-shadow: 2px 2px 5px rgba(0,0,0,0.6); }
    header p { font-size: 1.2em; text-shadow: 1px 1px 3px rgba(0,0,0,0.6); }

    /* Nav */
    nav {
      display: flex;
      justify-content: center;
      background: #333;
      padding: 10px;
      gap: 16px;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 6px;
      border-bottom: 2px solid transparent;
    }
    nav a:hover { color: var(--accent); }
    nav a.active { color: var(--accent); border-bottom-color: var(--accent); }

    /* Pages */
    main { padding: 0 10px 30px; }
    .page {
      display: none;
      padding: 40px 20px;
      max-width: 900px;
      margin: 20px auto 0;
      background: #fff;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    .page.active { display: block; }

    /* Home images */
    .home-images {
      display: flex; justify-content: center; gap: 20px; margin-top: 20px; flex-wrap: wrap;
    }
    .home-images .selfie img {
      width: 180px; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .home-images .barracks img {
      width: 400px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    /* Table */
    table { width: 100%; border-collapse: collapse; margin-top: 20px; }
    table, th, td { border: 1px solid #ccc; }
    th, td { padding: 10px; text-align: left; }
    th { background: #f2f2f2; }

    /* Artefacts (inside Learning) */
    #artefacts {
      background: #f5f0e6; padding: 2rem; border-radius: 8px; margin-top: 2rem;
    }
    #artefacts h2 { color: var(--brick); margin-top: 0; }
    .artefact-gallery {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1.5rem;
    }
    .artefact {
      position: relative; text-align: center; border: 2px solid #ccc; border-radius: 6px;
      overflow: hidden; background: #fff; box-shadow: 0 0 8px rgba(0,0,0,0.1); cursor: pointer;
    }
    .artefact img { width: 100%; height: 180px; object-fit: cover; display: block; }
    .caption { margin: 0.5rem 0 0.2rem; font-weight: 700; color: var(--brick); }

    /* Student & Teacher boxes */
    .student-prompt {
      background: var(--parchment); border-left: 4px solid var(--parchment-border);
      padding: 15px; margin-top: 20px; border-radius: 6px;
    }
    .student-prompt h3 { margin: 0 0 8px; color: #8a5a10; }
    .teachers-guide {
      background: var(--guide-bg); border-left: 4px solid var(--guide-border);
      padding: 15px; margin-top: 20px; border-radius: 6px;
    }
    .teachers-guide h4 { margin: 0 0 8px; color: #005fa3; }

    /* Video embed */
    .video-embed {
      position: relative; width: 100%; aspect-ratio: 16/9; background: #000;
      border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.15); margin-top: 8px;
    }
    .video-embed iframe { position: absolute; inset: 0; width: 100%; height: 100%; border: 0; }

    /* Site Context gallery */
    .gallery {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem; margin-top: 20px;
    }
    .gallery figure { margin: 0; text-align: center; }
    .gallery img { width: 100%; border-radius: 6px; box-shadow: 0 2px 6px rgba(0,0,0,0.15); }
    .gallery figcaption { margin-top: 6px; font-size: 0.9rem; color: #555; }

    /* Modal */
    .modal {
      display: none; position: fixed; z-index: 1000; inset: 0; background: rgba(0,0,0,0.8);
      padding: 20px; overflow: auto;
    }
    .modal[aria-hidden="false"] { display: block; }
    .modal-content {
      background: #fff; color: #333; margin: 40px auto; padding: 20px;
      width: 90%; max-width: 780px; border-radius: 10px; position: relative; text-align: center;
      box-shadow: 0 10px 30px rgba(0,0,0,0.35);
    }
    .modal-content img {
      width: 100%; max-height: 60vh; object-fit: contain; border-radius: 8px; margin-bottom: 12px;
    }
    .modal-title { margin: 8px 0 6px; font-size: 1.2rem; color: var(--brick); }
    .modal-desc { margin: 0 0 8px; }
    .close-btn {
      position: absolute; top: 10px; right: 12px; font-size: 28px; line-height: 1;
      background: transparent; border: 0; color: #333; cursor: pointer;
    }
    .close-btn:hover { color: #e00; }

    footer {
      text-align: center; background: #333; color: #fff; padding: 15px; margin-top: 20px;
    }

    @media (max-width: 520px) {
      header { padding: 60px 16px; }
      header h1 { font-size: 2em; }
      .home-images .barracks img { width: 100%; }
    }
  </style>
</head>
<body>
  <!-- HERO -->
  <header>
    <h1>Exploring Hyde Park Barracks: Life in Colonial Sydney</h1>
    <p>A Stage 2 History Learning Resource</p>
  </header>

  <!-- NAV -->
  <nav aria-label="Primary">
    <a href="#" class="active" onclick="return showPage('home', this)">Home</a>
    <a href="#" onclick="return showPage('site', this)">Site Context</a>
    <a href="#" onclick="return showPage('curriculum', this)">Curriculum Links</a>
    <a href="#" onclick="return showPage('learning', this)">Learning Experiences</a>
    <a href="#" onclick="return showPage('resources', this)">Supporting Resources</a>
    <a href="#" onclick="return showPage('reflection', this)">Critical Reflection</a>
  </nav>

  <main>
    <!-- HOME -->
    <section id="home" class="page active" aria-label="Home">
      <h2>Welcome</h2>
      <p>
        Welcome to this Stage 2 History resource, designed to connect classroom learning with the real-world context of Hyde Park Barracks. This website supports teachers and students in exploring colonial settlement, convict life, and the development of Sydney through inquiry-based learning. By engaging with photographs, activities, and historical sources, students can build a deeper understanding of how people lived in the past and why this World Heritage site is significant today.
      </p>
      <p><em>This resource was developed after visiting Hyde Park Barracks in Sydney, where I explored the convict hammocks, courtyards, and museum exhibits.</em></p>
      <div class="home-images">
        <div class="selfie"><img src="Selfie.jpg" alt="Selfie of the author at the site"></div>
        <div class="barracks"><img src="barracksfrontview.jpg" alt="Front view of Hyde Park Barracks"></div>
      </div>
    </section>

    <!-- SITE CONTEXT -->
    <section id="site" class="page" aria-label="Site Context">
      <h2>Hyde Park Barracks: A Window into Sydney’s Past</h2>
      <p>
        Hyde Park Barracks is a UNESCO World Heritage site located on Macquarie Street in Sydney’s CBD. Built in 1819 under Governor Lachlan Macquarie, and designed by convict architect Francis Greenway, the Barracks was central to the colony’s growth. For three decades, it housed male convicts who worked on roads, buildings, and other public works that shaped early Sydney. Later, it was repurposed as an immigration depot, particularly for Irish orphan girls, and then as an asylum for destitute women.
      </p>
      <p>
        The site is historically significant because it tells multiple stories: of colonial authority and convict labour, of migration and survival, and of institutional care. Today, Hyde Park Barracks operates as a museum, using its preserved buildings, archaeological remains, and artefact collections to connect modern Australians with the lived experiences of the past.
      </p>
      <p>
        For students, the Barracks offers a unique opportunity to investigate evidence firsthand, deepening their understanding of Australia’s colonial history and its lasting impacts.
      </p>
      <div class="gallery">
        <figure>
          <img src="hydebarrackext.jpg" alt="Barracks exterior">
          <figcaption>Designed by convict architect Francis Greenway, 1819.</figcaption>
        </figure>
        <figure>
          <img src="bed.jpg" alt="Dormitory hammocks">
          <figcaption>Convicts slept in crowded hammocks.</figcaption>
        </figure>
        <figure>
          <img src="courtyard.jpg" alt="Barracks courtyard">
          <figcaption>Central meeting and work area within the Barracks.</figcaption>
        </figure>
      </div>
    </section>

    <!-- CURRICULUM LINKS -->
    <section id="curriculum" class="page" aria-label="Curriculum Links">
      <h2>Curriculum Links</h2>
      <p>
        This resource supports the NSW History K–6 Syllabus (2024), particularly Stage 2 (Years 3–4). It aligns directly with HS2-HIS-01, focusing on how people lived in the Sydney Cove penal settlement and the use of sources as evidence. It also addresses general capabilities and cross-curriculum priorities, encouraging students to think critically, work collaboratively, and engage with Aboriginal and Torres Strait Islander perspectives.
      </p>
      <table>
        <tr>
          <th>Curriculum Area</th>
          <th>How Hyde Park Barracks Supports Learning</th>
        </tr>
        <tr>
          <td>HS2-HIS-01</td>
          <td>Students use historical sources (artefacts, maps, buildings) to explain what life was like in the Sydney Cove penal settlement.</td>
        </tr>
        <tr>
          <td>Cross-Curriculum Priorities</td>
          <td>Aboriginal and Torres Strait Islander Histories and Cultures are integrated by considering Indigenous perspectives of colonial expansion.</td>
        </tr>
        <tr>
          <td>General Capabilities</td>
          <td>Critical and Creative Thinking, Literacy, ICT Capability, and Personal and Social Capability are embedded in inquiry tasks.</td>
        </tr>
      </table>
      <p><a href="https://curriculum.nsw.edu.au/learning-areas/hsie/hsie-k-6-2024/overview" target="_blank" rel="noopener">
    Link to NSW History K–6 Syllabus (2024) </a></p>
    </section>

    <!-- LEARNING EXPERIENCES -->
    <section id="learning" class="page" aria-label="Learning Experiences">
      <h2>Learning Experiences</h2>


  <!-- LEARNING EXPERIENCE 1 -->
  <h3>Learning Experience 1: Life in the Barracks – A Convict’s Day</h3>
  <p><strong>Curriculum Focus:</strong> Stage 2 History – HS2-HIS-01: Explains how people lived in the past and what life was like in the Sydney Cove penal settlement using sources as evidence.</p>

  <p><strong>Overview:</strong> Students will immerse themselves in the experiences of convicts who lived and worked at Hyde Park Barracks in the 1820s. The activity begins with students exploring the Hyde Park Barracks Virtual Tour (Digital Resource 1). They will digitally "walk" through the dormitories and work areas, noting the lack of privacy and the crowded conditions. Next, students analyse high-quality images of Historical Artefact Displays (Physical Resource 1), focusing on hammocks, leg irons, and the crude texture of a convict uniform, inferring the harshness of daily life.</p>

  <p>To understand the journey before the Barracks, students analyse three short, curated excerpts from Surgeon Robert Espie’s Journal (Physical Resource 2), which detail shipboard punishment (e.g., the “Coal Hole”) and strict hygiene routines. Working in groups, students create a digital evidence table (Padlet/Google Docs) comparing the discipline and living conditions revealed by the Virtual Tour, the Artefacts, and the Surgeon’s Journal. Using their evidence, each student writes a creative journal entry or voice recording titled “A Day in My Life at the Barracks.” The lesson concludes with a reflective class discussion comparing the discipline and fairness shown in the sources to modern justice systems.</p>

  <p><strong>Pedagogical Approach:</strong> This inquiry-based experience uses constructivist and empathetic learning, combining evidence analysis from a visual tour, physical objects, and a primary text source. Assessment occurs through student journals and their evidence table. Differentiation is achieved through multimodal expression—students may write, record, or draw their reflections.</p>

  <p><strong>Inquiry Questions:</strong></p>
  <ul>
    <li>What was daily life like for convicts at Hyde Park Barracks?</li>
    <li>How do the Virtual Tour, the Artefacts, and the Surgeon’s Journal each help us understand convict discipline?</li>
    <li>Were rules and punishments fair in the 1820s?</li>
  </ul>

  <!-- EXPLORING ARTEFACTS -->
  <section id="artefacts" role="region" aria-label="Explore the Artefacts">
    <h2>Explore the Artefacts of Hyde Park Barracks</h2>
    <p class="subheading">Click on each artefact to discover how it was used and what it tells us about daily life in the Barracks.</p>

    <div class="artefact-gallery">
      <div class="artefact" onclick="openModal('bed.jpg','Convict Hammock','Convicts often slept two to a hammock in overcrowded rooms. The rooms were noisy, cramped, and smelly.')">
        <img src="bed.jpg" alt="Convict Hammock"><p class="caption">Convict Hammock</p>
      </div>
      <div class="artefact" onclick="openModal('ironleg.jpg','Leg Irons','Heavy iron chains locked around ankles as punishment for running away or breaking rules. They made it painful to move and work.')">
        <img src="ironleg.jpg" alt="Leg Irons"><p class="caption">Leg Irons</p>
      </div>
      <div class="artefact" onclick="openModal('ticketofleave.jpg','Ticket of Leave','A special pass allowing well-behaved convicts more freedom before their sentence ended. They could find work but still had restrictions.')">
        <img src="ticketofleave.jpg" alt="Ticket of Leave"><p class="caption">Ticket of Leave</p>
      </div>
      <div class="artefact" onclick="openModal('womensclothes.jpg','Women’s Clothing','Women who lived at the Barracks as immigrants or in the asylum wore plain, restrictive clothing.')">
        <img src="womensclothes.jpg" alt="Women’s Clothing"><p class="caption">Women’s Clothing</p>
      </div>
      <div class="artefact" onclick="openModal('whip.jpg','Whip','Whips were used for discipline and punishment. Convicts could be flogged publicly as a warning.')">
        <img src="whip.jpg" alt="Whip"><p class="caption">Whip</p>
      </div>
      <div class="artefact" onclick="openModal('rationticket1.jpg','Ration Ticket','Convicts received basic rations: bread, salted meat, and sometimes vegetables. Often poor quality and scarce.')">
        <img src="rationticket1.jpg" alt="Ration Ticket"><p class="caption">Ration Ticket</p>
      </div>
    </div>

    <div class="student-prompt">
      <h3>📝 Think & Share</h3>
      <ul>
        <li>Which artefact would you find hardest to live with? Why?</li>
        <li>What does this object tell us about daily life at Hyde Park Barracks?</li>
        <li>How might life have been different for men and women at the Barracks?</li>
      </ul>
    </div>

    <div class="teachers-guide">
      <h4>Teacher’s Guide</h4>
      <p><strong>Tip:</strong> Use this as a discussion starter. Project the artefact gallery and let students click to reveal info.</p>
      <ul>
        <li>Which artefact shocked you most?</li>
        <li>What do these objects reveal about rules and punishment?</li>
        <li>Would modern prisons look similar or different today?</li>
      </ul>
    </div>
  </section>

  <!-- LEARNING EXPERIENCE 2 -->
  <h3>Learning Experience 2: From Convicts to Migrants – Changing Stories Over Time</h3>
  <p><strong>Curriculum Focus:</strong> Stage 2 History – HS2-HIS-01: Explains how people lived in the past and how navigation connected the world, using sources as evidence.</p>

  <p><strong>Overview:</strong> Students explore how Hyde Park Barracks and its surrounding city evolved over time. The experience begins with students using Digital Resource 2 (Historical Map Comparison) to analyse the 1887 City of Sydney map alongside modern Google Maps. They will identify the Barracks' original strategic location and note how the land use changed as the city grew around it (continuity and change).</p>

  <p>Focusing on the Barracks' changing purpose, students trace the site's history from a Male Convict Barracks to the Female Immigration Depot. They analyse the final, highly judgmental excerpt of the Surgeon’s Journal (Physical Resource 2), capturing the final moment the female convicts were handed over to colonial boats. This is juxtaposed with the experiences of the later arriving female immigrants. Students then use their map analysis and the journal’s emotional account to write a first-person diary entry, imagining the anxieties and sights of arriving in Sydney and seeing the city for the first time—either as a disembarking convict (1823) or a new immigrant (1840s).</p>

  <p>The activity concludes with a class "Timeline Gallery Walk" where groups share their work, discussing how the changing architecture and surrounding environment (seen on the maps) reflect the change in the building's use and Australia's evolving social priorities.</p>

  <p><strong>Pedagogical Approach:</strong> This experience uses inquiry, digital mapping, and source comparison. Students become historians—analysing visual evidence (maps), synthesizing information about change, and communicating understanding creatively (diary entry). Assessment for learning occurs through the diary entries and class discussion. It integrates ICT capability, empathy, and historical reasoning, deepening conceptual understanding of continuity and change over time.</p>

  <p><strong>Inquiry Questions:</strong></p>
  <ul>
    <li>How did the location of the Barracks (seen on the maps) influence its different uses over time?</li>
    <li>What do the emotional accounts from the Surgeon’s Journal and the map changes tell us about the arrival experience in Sydney?</li>
    <li>How do changes to the building reflect changes in Australia's identity?</li>
  </ul>

  <!-- BONUS FUN QUIZ -->
  <h3>Bonus Fun Quiz: Would You Survive at Hyde Park Barracks?</h3>
  <form id="barracksQuiz">
    <div id="quiz">
      <div class="question">
        <p>1. If you were migrating to Sydney in 1820, which of these would be MOST important to pack?</p>
        <label><input type="radio" name="q1"> A mirror</label><br>
        <label><input type="radio" name="q1" data-correct="true"> A cooking pot</label><br>
        <label><input type="radio" name="q1"> A toy</label><br>
        <label><input type="radio" name="q1"> A garden hose</label>
      </div>

      <div class="question">
        <p>2. Convicts were given uniforms. Why?</p>
        <label><input type="radio" name="q2"> To keep them warm</label><br>
        <label><input type="radio" name="q2" data-correct="true"> To make them easy to identify</label><br>
        <label><input type="radio" name="q2"> To stop fights</label><br>
        <label><input type="radio" name="q2"> Because they liked stripes</label>
      </div>

      <div class="question">
        <p>3. What type of food were convicts most likely to eat at the Barracks?</p>
        <label><input type="radio" name="q3" data-correct="true"> Bread and salted meat</label><br>
        <label><input type="radio" name="q3"> Fresh fruit salad</label><br>
        <label><input type="radio" name="q3"> Roast chicken</label><br>
        <label><input type="radio" name="q3"> Chocolate and tea</label>
      </div>

      <div class="question">
        <p>4. Where did convicts usually sleep?</p>
        <label><input type="radio" name="q4"> Private beds</label><br>
        <label><input type="radio" name="q4"> On straw mats</label><br>
        <label><input type="radio" name="q4" data-correct="true"> In hammocks (sometimes two to a hammock)</label><br>
        <label><input type="radio" name="q4"> In wooden bunks</label>
      </div>

      <div class="question">
        <p>5. Why is Hyde Park Barracks important today?</p>
        <label><input type="radio" name="q5"> It’s a shopping centre</label><br>
        <label><input type="radio" name="q5" data-correct="true"> It’s a World Heritage museum that tells the stories of convicts and migrants</label><br>
        <label><input type="radio" name="q5"> It’s a military base</label><br>
        <label><input type="radio" name="q5"> It’s Governor Macquarie’s house</label>
      </div>

      <button type="button" onclick="checkQuiz()">Submit Answers</button>
      <button type="reset" onclick="resetQuiz()">Reset Quiz</button>
      <div id="quizResult"></div>
    </div>
  </form>

  <div class="teachers-guide">
    <h4>Discuss</h4>
    <p>Which answer surprised you most?</p>
    <p>Would you rather live as a convict, migrant, or modern student?</p>
  </div>
    </section>

    <!-- SUPPORTING RESOURCES -->
  <!-- RESOURCES PAGE -->
<section id="resources" class="page" aria-label="Resources">
  <h2>Supporting Resources</h2>

  <!-- DIGITAL RESOURCE 1 -->
  <div class="resource-section">
    <h3>Digital Resource 1 – Hyde Park Barracks Virtual Tour (VR/Online)</h3>
    <a href="http://embed.panedia.com/vtlite3/00001809?h=s" target="_blank">
      <img src="virtualtour.jpeg" alt="Hyde Park Barracks Virtual Tour" class="resource-img small-img">
    </a>
    <p>
      The Hyde Park Barracks Virtual Tour allows students to explore dormitories, artefacts, and museum spaces through a 360° virtual experience hosted via embed.panedia.com. 
      This free web-based tool can be accessed on laptops, tablets, or through VR headsets for a fully immersive experience. It supports Learning Experience 1 by enabling students 
      to virtually “step inside” the Barracks and engage with authentic spaces and artefacts such as hammocks, workrooms, and punishment areas. 
      Teachers can guide inquiry-based discussions as students navigate the tour, prompting reflection on daily convict life, fairness, and discipline. 
      This resource builds empathy, spatial understanding, and digital literacy through interactive, place-based learning.
    </p>
  </div>

  <!-- DIGITAL RESOURCE 2 -->
  <div class="resource-section">
    <h3>Digital Resource 2 – City of Sydney & Suburbs Map (1887) and Google Maps Comparison</h3>

    <div class="resource-gallery">
      <a href="https://www.google.com/maps/place/Hyde+Park+Barracks/@-33.8696036,151.212585,17z/data=!3m1!4b1!4m6!3m5!1s0x6b12ae6ad32b66bf:0xe17defded4a8ac4e!8m2!3d-33.8696036!4d151.212585!16zL20vMGJteHNn?entry=ttu&g_ep=EgoyMDI1MTAwMS4wIKXMDSoASAFQAw%3D%3D" target="_blank">
        <img src="google.png" alt="Google Maps – Hyde Park Barracks" class="small-img">
      </a>
      <a href="https://archives.cityofsydney.nsw.gov.au/nodes/view/1709401" target="_blank">
        <img src="comparingmap.jpeg" alt="1887 City of Sydney Map" class="small-img">
      </a>
    </div>

    <p>
      The City of Sydney & Suburbs, 1887 map (available at City of Sydney Archives) offers a detailed historical view of colonial Sydney, including Hyde Park Barracks and surrounding landmarks. 
      This online resource includes a Google Maps overlay that allows direct comparison between 19th-century Sydney and its modern urban landscape. 
      Students use this alongside Google Maps to locate Hyde Park Barracks today, exploring nearby sites such as St Mary’s Cathedral, The Domain, and Macquarie Street.
    </p>
    <p>
      By examining both maps side by side, students can identify continuity and change in land use, architecture, and street planning. 
      Teachers can prompt discussion through inquiry questions such as: 
      “Why was the Barracks built here in 1819?” or “What features of the 1887 map remain visible today?”
      This resource supports Learning Experience 2 by combining historical inquiry, digital mapping, and visual analysis. 
      It helps students make spatial and temporal connections between past and present Sydney while developing digital literacy and critical thinking. 
      Comparing maps across time also reinforces key historical concepts—continuity, change, cause, and significance—in an authentic, place-based context.
    </p>
  </div>

  <!-- PHYSICAL RESOURCE 1 -->
  <div class="resource-section">
    <h3>Physical/Visual Resource 1 – Historical Artefact Displays</h3>
    <div class="artefact-gallery">
      <div class="artefact"><img src="bed.jpg" alt="Convict Hammock"><p class="caption">Convict Hammock</p></div>
      <div class="artefact"><img src="ironleg.jpg" alt="Leg Irons"><p class="caption">Leg Irons</p></div>
      <div class="artefact"><img src="ticketofleave.jpg" alt="Ticket of Leave"><p class="caption">Ticket of Leave</p></div>
      <div class="artefact"><img src="womensclothes.jpg" alt="Women’s Clothing"><p class="caption">Women’s Clothing</p></div>
      <div class="artefact"><img src="whip.jpg" alt="Whip"><p class="caption">Whip</p></div>
      <div class="artefact"><img src="rationticket1.jpg" alt="Ration Ticket"><p class="caption">Ration Ticket</p></div>
    </div>

    <p>
      The museum’s physical artefact collections—such as convict hammocks, leg irons, and institutional women’s clothing—provide tangible evidence of life at the Barracks. 
      These artefacts can be viewed on-site or through high-quality photographs and replicas in the classroom. 
      They are integral to Learning Experience 1, helping students infer meaning from real historical evidence. 
      Teachers can use artefact images as source analysis prompts, supporting historical inquiry and observation skills. 
      By engaging with authentic physical objects, students develop a deeper emotional and sensory understanding of Australia’s colonial history 
      and the human experiences behind it.
    </p>
  </div>

  <!-- PHYSICAL RESOURCE 2 – SURGEON’S JOURNAL -->
  <div class="resource-section">
    <h3>Physical/Visual Resource 2 – Surgeon’s Journal Transcript (Lord Sidmouth, 1823)</h3>
    <p>
      Resource: Curated excerpts from the transcribed journal of Surgeon Robert Espie, who oversaw the female convict voyage on the Lord Sidmouth to Sydney. 
      The excerpts detail daily routine, hygiene practices (scrubbing), specific punishments (the "Coal Hole"), and the surgeon's personal, judgmental relief 
      upon handing the women over to colonial authorities in Sydney.
    </p>

    <h4>The Surgeon’s Logbook: Discipline on the Journey</h4>
    <p>
      "Before the convicts reached Hyde Park Barracks, they spent months on a ship called the Lord Sidmouth. 
      The Surgeon, Robert Espie, kept a daily log of the strict rules and punishments. 
      Read his three main entries below and see how tough life was!"
    </p>

    <div class="logbook">
      <div class="log-card">
        <h4>🧼 Rule 1: Cleanliness</h4>
        <p class="quote">"Stow'd the beds and bedding upon Deck, and made the women <span>scrub and cleanse</span> every part of the prison before Breakfast – I find them very tractable and kindly."</p>
        <p class="inquiry">Your Task: What does this rule tell you about the health of the women and the state of the ship?</p>
      </div>

      <div class="log-card">
        <h4>⛓️ Rule 2: Punishment</h4>
        <p class="quote">"Handcuffed Elizabeth Kinsey and Mary Brown together and put them into the <span>Coal Hole</span> for abusive and mutinous conduct..."</p>
        <p class="inquiry">Your Task: The Coal Hole was a tiny, dark space. Why do you think the Surgeon said this punishment was necessary? Was it fair?</p>
      </div>

      <div class="log-card">
        <h4>🚢 Rule 3: Handover</h4>
        <p class="quote">"At 7am the Government's boats destined to carry them to Parramatta came alongside... I cannot but express my great joy at having got rid of so troublesome a charge."</p>
        <p class="inquiry">Your Task: What does this final entry tell you about how the Surgeon viewed the women? How do you think the women felt when they were described this way?</p>
      </div>
    </div>

    <p><em>Source:</em> Excerpts from the Surgeon’s Journal of Mr. Robert Espie, R.N., Convict Ship <em>Lord Sidmouth</em> (1823).<br>
    <a href="#" target="_blank">Teachers wishing to view the full original transcript can access it here.</a></p>

    <p>
      This text-based primary source is invaluable as it provides a direct, highly emotive account of the convict experience before their entry into the colonial system. 
      For Learning Experience 1, the journal entries vividly illustrate the harsh discipline and routine (e.g., forced scrubbing and the "Coal Hole" punishment) that convicts faced, 
      allowing students to compare shipboard life with the Barracks discipline. For Learning Experience 2, the excerpt recording the surgeon’s judgemental relief upon arrival serves as a 
      powerful historical counterpoint. It establishes the challenging human experience of arrival, which students can then juxtapose with the less-coerced arrival of later immigrants, 
      supporting the analysis of change over time at the Barracks. The clear, short excerpts are ideal for Stage 2 students to use as specific evidence in their historical writing.
    </p>
  </div>

  <!-- BONUS VIDEO -->
  <div class="resource-section">
    <h3>Bonus Resource – Walkthrough Video</h3>
    <div class="video-embed">
      <iframe 
        src="https://www.youtube.com/embed/YWUyGwPr-7o" 
        title="Hyde Park Barracks Museum Walkthrough" 
        allowfullscreen
        style="aspect-ratio: 16/9; width: 100%; max-width: 700px; border: none; border-radius: 10px;">
      </iframe>
    </div>
  </div>
</section>

<style>
  .resource-section { margin-bottom: 60px; }
  .resource-gallery, .artefact-gallery { display: flex; flex-wrap: wrap; gap: 15px; justify-content: center; }
  .small-img { width: 280px; max-width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
  .artefact img { width: 140px; border-radius: 6px; box-shadow: 0 1px 4px rgba(0,0,0,0.1); }
  .caption { text-align: center; font-size: 0.9rem; margin-top: 4px; }
  .logbook { display: flex; flex-direction: column; gap: 20px; margin-top: 20px; }
  .log-card { background: #f9f9f9; border-left: 5px solid #003366; padding: 15px; border-radius: 8px; }
  .log-card h4 { margin-top: 0; color: #003366; }
  .quote span { color: darkred; font-weight: bold; }
  .video-embed { text-align: center; margin-top: 20px; }
</style>

</section>

<style>
  .resource-section { margin-bottom: 60px; }
  .resource-gallery, .artefact-gallery { display: flex; flex-wrap: wrap; gap: 15px; justify-content: center; }
  .small-img { width: 300px; max-width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
  .artefact img { width: 150px; border-radius: 6px; box-shadow: 0 1px 4px rgba(0,0,0,0.1); }
  .caption { text-align: center; font-size: 0.9rem; margin-top: 4px; }
  .logbook { display: flex; flex-direction: column; gap: 20px; margin-top: 20px; }
  .log-card { background: #f9f9f9; border-left: 5px solid #003366; padding: 15px; border-radius: 8px; }
  .log-card h4 { margin-top: 0; color: #003366; }
  .quote span { color: darkred; font-weight: bold; }
  .video-embed { text-align: center; margin-top: 20px; }
  .video-embed iframe { width: 560px; height: 315px; max-width: 100%; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.2); }
</style>


</section>

    <!-- CRITICAL REFLECTION -->
   <!-- CRITICAL REFLECTION PAGE -->
<section id="reflection" class="page" aria-label="Critical Reflection">
  <h2>Critical Reflection</h2>

  <p>
    This digital resource demonstrates how authentic, community-based learning can transform students’ understanding of history through inquiry, empathy, and engagement. 
    Hyde Park Barracks, as a living historical site, provides a tangible context through which Stage 2 students can explore the NSW History Syllabus outcome 
    <strong>HS2-HIS-01</strong> — explaining how people lived in the past and using sources as evidence. By connecting curriculum outcomes to a real-world site, the resource situates learning 
    in an authentic context that promotes curiosity, higher-order thinking, and civic awareness.
  </p>

  <p>
    The first learning experience, <em>“Life in the Barracks – A Convict’s Day,”</em> immerses students in the sensory and emotional realities of convict life through multimodal evidence — 
    artefacts, journal excerpts, and a 360° virtual tour. This reflects constructivist pedagogy (<strong>Vygotsky, 1978</strong>), as students actively construct understanding through interaction 
    with authentic materials. By analysing multiple historical sources and then writing a creative journal entry, students demonstrate both factual comprehension and empathetic engagement. 
    This task aligns with <strong>Wright-Maley’s (2016)</strong> historical thinking concepts, particularly “historical perspectives” and “evidence,” encouraging learners to reconstruct the past 
    while recognising the limits of their knowledge. The use of digital tools like VR tours also supports multimodal literacy and ICT Capability, providing inclusive access to place-based learning 
    even beyond the physical site visit.
  </p>

  <p>
    The second learning experience, <em>“From Convicts to Migrants – Changing Stories Over Time,”</em> extends inquiry learning through the concepts of continuity and change. Students compare 
    the 1887 City of Sydney map with modern Google Maps to visualise how urban development reflects evolving social priorities. This digital comparison fosters spatial reasoning and temporal 
    awareness, core skills in both geographical and historical inquiry. By linking visual mapping with primary text sources (the surgeon’s journal), the experience encourages synthesis across 
    media, demonstrating how evidence from different times and perspectives can deepen understanding. This activity also integrates critical and creative thinking, as students interpret change 
    through a narrative lens — imagining the emotions of arriving convicts or immigrants.
  </p>

  <p>
    Across both experiences, the resource integrates high-impact teaching strategies such as questioning, discussion, and metacognitive reflection (<strong>Hattie, 2012; Killen & O’Toole, 2022</strong>). 
    It positions students as historians, engaging them in active meaning-making rather than passive reception. This approach reflects inquiry-based learning principles (<strong>Yemini et al., 2023</strong>), 
    where students generate and investigate their own questions about the past, fostering ownership and curiosity.
  </p>

  <p>
    Importantly, the resource also embeds cross-curriculum priorities, including Aboriginal and Torres Strait Islander perspectives. By acknowledging that Hyde Park Barracks stands on Gadigal land, 
    it prompts reflection on colonisation and the ongoing impacts on Indigenous communities, aligning with the Australian Curriculum’s commitment to reconciliation and shared histories.
  </p>

  <p>
    Pedagogically, the digital format itself enhances accessibility and engagement. The integration of interactive features — VR exploration, hover-over hotspots, and embedded quizzes — transforms 
    historical learning into an active, student-centred experience. These strategies not only engage diverse learners but also model how technology can authentically extend place-based inquiry beyond the classroom.
  </p>

  <p>
    In conclusion, this resource exemplifies how community sites like Hyde Park Barracks can enrich HaSS education through inquiry, empathy, and digital engagement. 
    By combining authentic evidence with reflective, multimodal pedagogy, the resource cultivates deeper historical understanding and helps develop active and informed citizens — 
    a core aim of Humanities and Social Sciences education.
  </p>

  <!-- REFERENCES SECTION -->
  <h3>References</h3>
  <ul class="references">
    <li>Hattie, J. (2012). <em>Visible learning for teachers: Maximizing impact on learning</em> (1st ed.). Routledge. <a href="https://doi.org/10.4324/9780203181522" target="_blank">https://doi.org/10.4324/9780203181522</a></li>
    <li>Killen, R., & O’Toole, M. (2022). <em>Effective teaching strategies: Lessons from research and practice</em> (8th ed.). Cengage Learning.</li>
    <li>NESA. (2024). <em>Human society and its environment K–6 – Outcomes | NSW curriculum | NSW Education Standards Authority.</em> Curriculum.nsw.edu.au. <a href="https://curriculum.nsw.edu.au/learning-areas/hsie/hsie-k-6-2024/outcomes" target="_blank">https://curriculum.nsw.edu.au/learning-areas/hsie/hsie-k-6-2024/outcomes</a></li>
    <li>Vygotsky, L. S. (1978). <em>Mind in society: The development of higher psychological processes.</em> Harvard University Press. <a href="https://doi.org/10.1017/s0033291700041507" target="_blank">https://doi.org/10.1017/s0033291700041507</a></li>
    <li>Wright-Maley, C. (2016). The big six: Historical thinking concepts. <em>The Journal of Social Studies Research, 40</em>(3), 233–235. <a href="https://doi.org/10.1016/j.jssr.2015.09.003" target="_blank">https://doi.org/10.1016/j.jssr.2015.09.003</a></li>
    <li>Yemini, M., Engel, L., & Ben Simon, A. (2023). Place-based education: A systematic review of literature. <em>Educational Review, 77</em>(2), 1–21. <a href="https://doi.org/10.1080/00131911.2023.2177260" target="_blank">https://doi.org/10.1080/00131911.2023.2177260</a></li>
  </ul>
</section>

<style>
  .references {
    list-style-type: none;
    padding-left: 0;
    margin-top: 20px;
  }
  .references li {
    margin-bottom: 10px;
    line-height: 1.5;
  }
  .references a {
    color: #003366;
    text-decoration: underline;
  }
</style>

    </section>
  </main>

  <!-- MODAL (shared for all artefacts) -->
  <div id="artefactModal" class="modal" aria-hidden="true" role="dialog" aria-labelledby="modalTitle">
    <div class="modal-content">
      <button class="close-btn" aria-label="Close" onclick="closeModal()">×</button>
      <img id="modalImg" src="" alt="">
      <h3 id="modalTitle" class="modal-title"></h3>
      <p id="modalDesc" class="modal-desc"></p>
    </div>
  </div>

  <!-- FOOTER -->
  <footer>
    <p>&copy; 2025 Hyde Park Barracks Learning Resource</p>
  </footer>

  <script>
    // Toggle only top-level pages
    function showPage(id, linkEl) {
      document.querySelectorAll('.page').forEach(s => s.classList.remove('active'));
      const target = document.getElementById(id);
      if (target) target.classList.add('active');

      document.querySelectorAll('nav a').forEach(a => a.classList.remove('active'));
      if (linkEl) linkEl.classList.add('active');

      window.scrollTo({ top: 0, behavior: 'smooth' });
      return false; // prevent anchor navigation
    }

    // Modal controls
    const modal = document.getElementById('artefactModal');
    const modalImg = document.getElementById('modalImg');
    const modalTitle = document.getElementById('modalTitle');
    const modalDesc = document.getElementById('modalDesc');

    function openModal(src, title, desc) {
      modalImg.src = src;
      modalImg.alt = title;
      modalTitle.textContent = title;
      modalDesc.textContent = desc;
      modal.setAttribute('aria-hidden', 'false');
      document.body.style.overflow = 'hidden'; // prevent background scroll
    }

    function closeModal() {
      modal.setAttribute('aria-hidden', 'true');
      modalImg.src = '';
      document.body.style.overflow = '';
    }

    // Close when clicking outside the dialog content
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });

    // Close on Escape
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.getAttribute('aria-hidden') === 'false') {
        closeModal();
      }
    });
  </script>
    <script>
function checkQuiz() {
  const quiz = document.getElementById("barracksQuiz");
  const questions = quiz.querySelectorAll(".question");
  let score = 0;
  const total = questions.length;

  questions.forEach((question) => {
    const selected = question.querySelector("input[type='radio']:checked");
    if (selected && selected.dataset.correct === "true") {
      score++;
      question.style.backgroundColor = "#d4edda"; // light green for correct
    } else {
      question.style.backgroundColor = "#f8d7da"; // light red for incorrect
    }
  });

  const result = document.getElementById("quizResult");
  result.innerHTML = `<h4>🎉 You scored ${score} out of ${total}!</h4>
    <p>${score === total ? "Amazing! You’d survive the Barracks easily!" :
    score >= 3 ? "Good effort! Life in the Barracks would be tough, but you’d manage." :
    "Ouch! The Barracks might be a hard place for you. Try again!"}</p>`;
  result.style.padding = "10px";
  result.style.borderRadius = "8px";
  result.style.backgroundColor = "#f0f0f0";
  result.style.marginTop = "15px";
}

function resetQuiz() {
  const questions = document.querySelectorAll("#barracksQuiz .question");
  questions.forEach(q => q.style.backgroundColor = "");
  document.getElementById("quizResult").innerHTML = "";
}
</script>
<script>
  // Function to count words inside a section
  function countWordsInSection(section) {
    const text = section.innerText || section.textContent;
    const words = text.trim().split(/\s+/).filter(word => word.length > 0);
    return words.length;
  }

  // Apply counts to all sections with class "page"
  document.addEventListener("DOMContentLoaded", function () {
    const sections = document.querySelectorAll(".page");
    sections.forEach(section => {
      const wordCount = countWordsInSection(section);
      const counter = document.createElement("p");
      counter.classList.add("word-count");
      counter.textContent = `Word count: ${wordCount}`;
      section.appendChild(counter);
    });
  });
</script>

<style>
  .word-count {
    font-size: 0.9em;
    color: #555;
    font-style: italic;
    margin-top: 20px;
    text-align: right;
  }
</style>

</body>
</html>
