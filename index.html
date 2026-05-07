<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Stateless Persons Digital Twin — UN 1954 Convention Framework</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --bg-primary: #ffffff;
    --bg-secondary: #f5f4f0;
    --bg-tertiary: #eeede8;
    --text-primary: #1a1a18;
    --text-secondary: #6b6a66;
    --text-tertiary: #9a9890;
    --border: rgba(0,0,0,0.12);
    --border-md: rgba(0,0,0,0.2);
    --radius-md: 8px;
    --radius-lg: 12px;
    --font-sans: 'Inter', system-ui, sans-serif;
    --font-mono: 'JetBrains Mono', 'Fira Code', monospace;
    --success-bg: #eaf3de; --success-text: #3b6d11;
    --warning-bg: #faeeda; --warning-text: #854f0b;
    --danger-bg: #fcebeb; --danger-text: #a32d2d;
    --info-bg: #e6f1fb; --info-text: #185fa5;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg-primary: #1e1e1c; --bg-secondary: #2a2a28; --bg-tertiary: #161614;
      --text-primary: #e8e6df; --text-secondary: #9a9890; --text-tertiary: #6b6a66;
      --border: rgba(255,255,255,0.1); --border-md: rgba(255,255,255,0.2);
      --success-bg: #173404; --success-text: #c0dd97;
      --warning-bg: #412402; --warning-text: #fac775;
      --danger-bg: #501313; --danger-text: #f7c1c1;
      --info-bg: #042c53; --info-text: #b5d4f4;
    }
  }
  body { font-family: var(--font-sans); background: var(--bg-tertiary); color: var(--text-primary); min-height: 100vh; padding: 24px; }
  h1 { font-size: 20px; font-weight: 500; margin-bottom: 4px; }
  .subtitle { font-size: 13px; color: var(--text-secondary); margin-bottom: 20px; }
  .toprow { display: grid; grid-template-columns: repeat(4, 1fr); gap: 12px; margin-bottom: 16px; }
  .mc { background: var(--bg-secondary); border-radius: var(--radius-md); padding: 13px 15px; }
  .mc-l { font-size: 11px; color: var(--text-secondary); margin-bottom: 4px; }
  .mc-v { font-size: 22px; font-weight: 500; color: var(--text-primary); }
  .body { display: grid; grid-template-columns: 282px 1fr; gap: 14px; align-items: start; }
  .card { background: var(--bg-primary); border: 0.5px solid var(--border); border-radius: var(--radius-lg); overflow: hidden; }
  .cp { padding: 16px; }
  .tabs { display: flex; border-bottom: 0.5px solid var(--border); overflow-x: auto; }
  .tab { padding: 10px 12px; font-size: 12px; color: var(--text-secondary); cursor: pointer; border: none; background: none; border-bottom: 2px solid transparent; margin-bottom: -1px; white-space: nowrap; display: flex; align-items: center; gap: 5px; }
  .tab.on { color: var(--text-primary); border-bottom-color: var(--text-primary); font-weight: 500; }
  .pane { display: none; padding: 16px; }
  .pane.on { display: block; }
  .sec { font-size: 10px; font-weight: 500; color: var(--text-secondary); letter-spacing: .06em; text-transform: uppercase; margin: 0 0 10px; }
  .fr { display: flex; justify-content: space-between; align-items: flex-start; padding: 6px 0; border-bottom: 0.5px solid var(--border); font-size: 12px; gap: 8px; }
  .fr:last-child { border-bottom: none; }
  .fr-l { color: var(--text-secondary); flex-shrink: 0; }
  .fr-v { font-weight: 500; text-align: right; line-height: 1.4; }
  .badge { padding: 2px 9px; border-radius: 100px; font-size: 11px; font-weight: 500; display: inline-flex; align-items: center; gap: 4px; }
  .b-r { background: var(--danger-bg); color: var(--danger-text); }
  .b-w { background: var(--warning-bg); color: var(--warning-text); }
  .b-i { background: var(--info-bg); color: var(--info-text); }
  .b-s { background: var(--success-bg); color: var(--success-text); }
  .rbar { margin-bottom: 9px; }
  .rbar-h { display: flex; justify-content: space-between; font-size: 11px; color: var(--text-secondary); margin-bottom: 3px; }
  .rbar-bg { height: 5px; border-radius: 3px; background: var(--border); }
  .rbar-f { height: 5px; border-radius: 3px; transition: width .55s ease; }
  .ai { display: flex; gap: 9px; padding: 8px 0; border-bottom: 0.5px solid var(--border); }
  .ai:last-child { border-bottom: none; }
  .ai-n { width: 20px; height: 20px; border-radius: 50%; font-size: 10px; font-weight: 500; display: flex; align-items: center; justify-content: center; flex-shrink: 0; margin-top: 1px; }
  .n-c { background: var(--success-bg); color: var(--success-text); }
  .n-p { background: var(--warning-bg); color: var(--warning-text); }
  .n-n { background: var(--danger-bg); color: var(--danger-text); }
  .ai-t { font-size: 12px; font-weight: 500; margin: 0 0 2px; }
  .ai-d { font-size: 11px; color: var(--text-secondary); margin: 0; line-height: 1.4; }
  .sg { display: grid; grid-template-columns: repeat(auto-fit, minmax(128px, 1fr)); gap: 9px; }
  .sc-c { background: var(--bg-secondary); border-radius: var(--radius-md); padding: 10px 11px; }
  .sc-n { font-size: 10px; color: var(--text-secondary); font-weight: 500; margin: 0 0 2px; }
  .sc-t { font-size: 11px; font-weight: 500; margin: 0 0 7px; line-height: 1.3; color: var(--text-primary); }
  .sc-b { height: 4px; border-radius: 2px; background: var(--border); }
  .sc-f { height: 4px; border-radius: 2px; transition: width .55s; }
  .sc-p { font-size: 10px; color: var(--text-secondary); margin: 3px 0 0; }
  .ps { display: flex; gap: 11px; margin-bottom: 12px; }
  .si-col { display: flex; flex-direction: column; align-items: center; }
  .s-circ { width: 26px; height: 26px; border-radius: 50%; border: 2px solid; display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 500; flex-shrink: 0; }
  .s-line { width: 2px; flex: 1; min-height: 14px; background: var(--border); margin: 2px 0; }
  .sk { flex: 1; padding-bottom: 10px; }
  .sk-t { font-size: 13px; font-weight: 500; margin: 2px 0 4px; color: var(--text-primary); }
  .sk-d { font-size: 11px; color: var(--text-secondary); line-height: 1.5; margin: 0 0 5px; }
  .tag { display: inline-block; padding: 2px 7px; border-radius: 3px; font-size: 10px; margin: 2px 2px 0 0; }
  .tag-r { background: var(--danger-bg); color: var(--danger-text); }
  .tag-g { background: var(--success-bg); color: var(--success-text); }
  .avt { width: 46px; height: 46px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 16px; font-weight: 500; margin-bottom: 9px; background: var(--info-bg); color: var(--info-text); }
  .mono { font-family: var(--font-mono); font-size: 10px; color: var(--text-tertiary); }
  .legend-row { display: flex; gap: 14px; margin-bottom: 10px; font-size: 11px; color: var(--text-secondary); flex-wrap: wrap; }
  .legend-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 4px; vertical-align: middle; }
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 11px; margin-bottom: 14px; }
  .info-note { font-size: 11px; color: var(--text-secondary); line-height: 1.5; margin-top: 12px; padding-top: 12px; border-top: 0.5px solid var(--border); }
  select, button { font-family: var(--font-sans); font-size: 13px; border-radius: var(--radius-md); border: 0.5px solid var(--border-md); background: var(--bg-primary); color: var(--text-primary); padding: 8px 10px; cursor: pointer; width: 100%; }
  button { background: var(--bg-secondary); transition: background 0.15s; }
  button:hover { background: var(--bg-tertiary); }
  @media (max-width: 700px) {
    .toprow { grid-template-columns: repeat(2, 1fr); }
    .body { grid-template-columns: 1fr; }
  }
  footer { margin-top: 24px; font-size: 11px; color: var(--text-tertiary); text-align: center; line-height: 1.7; }
  footer a { color: var(--text-secondary); }
</style>
</head>
<body>

<h1>Stateless Persons Digital Twin</h1>
<p class="subtitle">UN 1954 Convention on the Status of Stateless Persons · UNHCR #IBelong · SDG 16.9 · Proxy migration data</p>

<div class="toprow">
  <div class="mc"><p class="mc-l">UNHCR identified stateless</p><p class="mc-v">4.4M+</p></div>
  <div class="mc"><p class="mc-l">states with stateless populations</p><p class="mc-v">95</p></div>
  <div class="mc"><p class="mc-l">UN statelessness conventions</p><p class="mc-v">1954 · 1961</p></div>
  <div class="mc"><p class="mc-l">SDG 16.9 — legal identity by</p><p class="mc-v">2030</p></div>
</div>

<div class="body">
  <div class="card cp">
    <p class="sec">population category</p>
    <select id="popSel" onchange="generateTwin()" style="margin-bottom:10px">
      <option value="rohingya">Rohingya — Myanmar / Bangladesh</option>
      <option value="bidun">Bidun — Gulf states</option>
      <option value="roma">Roma — Eastern Europe</option>
      <option value="nubian">Nubian-Kenyan — Kenya</option>
      <option value="haitian">Haitian-Dominican — Dominican Republic</option>
      <option value="fsu">Post-Soviet stateless — Baltic / CIS</option>
    </select>
    <button style="margin-bottom:16px" onclick="generateTwin()">↻ Regenerate twin</button>
    <div id="personaDiv"></div>
  </div>

  <div class="card" style="min-height:500px">
    <div class="tabs">
      <button class="tab on" onclick="switchTab('rights',this)"><i class="ti ti-shield-half"></i> Rights map</button>
      <button class="tab" onclick="switchTab('risk',this)"><i class="ti ti-alert-triangle"></i> Risk factors</button>
      <button class="tab" onclick="switchTab('pathway',this)"><i class="ti ti-route"></i> Solutions</button>
      <button class="tab" onclick="switchTab('goals',this)"><i class="ti ti-target"></i> UN goals</button>
    </div>

    <div id="rights" class="pane on">
      <p class="sec">rights access vs 1954 Convention standard</p>
      <div class="legend-row">
        <span><span class="legend-swatch" style="background:#378ADD;opacity:.5;border:1px dashed #378ADD"></span>Convention standard (100%)</span>
        <span><span class="legend-swatch" style="background:#1D9E75"></span>Current access</span>
      </div>
      <div style="position:relative;height:220px;margin-bottom:14px">
        <canvas id="radarChart" role="img" aria-label="Radar chart showing rights access levels for the selected stateless population">Rights radar chart loading...</canvas>
      </div>
      <div id="rightsDetail"></div>
    </div>

    <div id="risk" class="pane">
      <p class="sec">vulnerability & risk profile</p>
      <div id="riskContent"></div>
    </div>

    <div id="pathway" class="pane">
      <p class="sec">pathway to durable solutions</p>
      <div id="pathwayContent"></div>
    </div>

    <div id="goals" class="pane">
      <p class="sec">UNHCR 10-point action plan — #IBelong</p>
      <div id="unhcrActions" style="margin-bottom:18px"></div>
      <p class="sec">SDG alignment</p>
      <div id="sdgGrid"></div>
    </div>
  </div>
</div>

<footer>
  Data sources: UNHCR Global Trends Report · Institute on Statelessness and Inclusion · Open Society Justice Initiative ·
  European Network on Statelessness · UN Treaty Collection ·
  <a href="https://www.unhcr.org/ibelong/" target="_blank">UNHCR #IBelong Campaign</a> ·
  <a href="https://sdgs.un.org/goals/goal16" target="_blank">SDG 16.9</a><br>
  This is a prototype digital twin using proxy/aggregate data. Individual profiles are synthetically generated for illustration.
</footer>

<script>
const POP = {
  rohingya:{label:'Rohingya',region:"Cox's Bazar, Bangladesh",origin:'Myanmar (Rakhine State)',est:'600,000+',statelessYrs:40,ageRange:[18,55],riskLevel:'extreme',doc:'None — no NRC, no birth certificate',housing:'Kutupalong refugee camp',
    rights:{identity:5,travel:3,education:28,employment:12,healthcare:22,housing:15,legal:8,movement:6},
    risks:{duration:95,documentation:98,confinement:92,childStateless:97,genderDisc:78,exploitation:90},
    actions:[{s:'n',t:'Resolve statelessness situation',d:"Myanmar's 1982 Citizenship Law excludes Rohingya by ethnicity. No bilateral resolution mechanism exists."},{s:'n',t:'No child born stateless',d:'Children in Bangladesh inherit statelessness; no birth registration pathway for Rohingya in camps.'},{s:'p',t:'Protection status granted',d:'UNHCR registers as refugees in Bangladesh; no formal statelessness determination (SSD) conducted.'},{s:'n',t:'Remove gender discrimination',d:'Ethnic exclusion under 1982 law is not gender-based; law itself has not been reformed.'},{s:'n',t:'Prevent statelessness via succession',d:'Not applicable — ongoing policy of ethnic exclusion by Myanmar state.'},{s:'n',t:'Birth registration for all',d:'Births in camps largely unregistered. UNICEF pilots underway; coverage below 15%.'},{s:'p',t:'Regularise stateless migrants',d:'Bangladesh issues UNHCR/GoB camp ID cards — not legal residency or citizenship.'},{s:'n',t:'Issue nationality documentation',d:'No pathway to Bangladeshi or Myanmar nationality currently exists for Rohingya.'},{s:'p',t:'Accede to UN conventions',d:"Bangladesh signed 1951 Refugee Convention but is not party to 1954 or 1961 statelessness conventions."},{s:'n',t:'Improve statelessness data',d:'2017 UNHCR profiling incomplete; estimates range from 600k to 1M+ stateless Rohingya globally.'}],
    sdg:{s1:20,s3:18,s4:25,s8:10,s107:30,s161:15,s163:8,s169:2},
    pathway:[{t:'Statelessness determination',d:'UNHCR SSD not systematically applied. Most registered as refugees, masking the statelessness dimension.',barriers:['No SSD system in Bangladesh','Myanmar rejects all returnees'],enablers:['UNHCR registration infrastructure'],done:false},{t:'Civil documentation access',d:'No travel document, birth certificate, or national ID available from Myanmar or Bangladesh.',barriers:['No bilateral agreement','1982 Myanmar Citizenship Law'],enablers:['Camp ration cards (limited function)'],done:false},{t:'Local integration or resettlement',d:'Bangladesh policy prohibits local integration. Third-country resettlement severely bottlenecked.',barriers:['Closed border policy','Global resettlement deficit'],enablers:['UNHCR resettlement pipeline (small)'],done:false},{t:'Voluntary return with nationality',d:'Return to Myanmar is conditional on nationality restoration, which Myanmar government refuses.',barriers:['Ongoing persecution','No citizenship guarantee','Safety conditions unmet'],enablers:[],done:false}]},
  bidun:{label:'Bidun',region:'Kuwait, UAE, Saudi Arabia',origin:'Gulf states (tribal/nomadic origin)',est:'~100,000 in Kuwait',statelessYrs:30,ageRange:[20,60],riskLevel:'high',doc:'Expired alien passports or no document',housing:'Urban — restricted residential areas',
    rights:{identity:30,travel:20,education:55,employment:42,healthcare:48,housing:52,legal:35,movement:58},
    risks:{duration:72,documentation:75,confinement:20,childStateless:80,genderDisc:65,exploitation:60},
    actions:[{s:'p',t:'Resolve statelessness situation',d:"Kuwait's Central Agency for Bidun Affairs exists but offers no nationality pathway."},{s:'p',t:'No child born stateless',d:'Bidun status is inherited; Kuwaiti law allows some birth registration through Bidun agency.'},{s:'p',t:'Protection status granted',d:'Kuwait provides de facto tolerated status without formal statelessness determination.'},{s:'p',t:'Remove gender discrimination',d:'Limited post-2014 reforms allow some women to pass nationality to children.'},{s:'n',t:'Prevent statelessness via succession',d:"Bidun excluded at Kuwait's independence in 1961; no retrospective remedy."},{s:'p',t:'Birth registration for all',d:'Some births registered through Bidun Affairs Agency; not universally applied.'},{s:'p',t:'Regularise stateless migrants',d:'Bidun hold tolerated status with limited employment and health access.'},{s:'n',t:'Issue nationality documentation',d:'No naturalisation pathway. 2011 Comoros passport scheme rejected by Bidun community.'},{s:'n',t:'Accede to UN conventions',d:'Kuwait not party to 1954 or 1961 statelessness conventions.'},{s:'p',t:'Improve statelessness data',d:'Partial census data available; Gulf states restrict independent research access.'}],
    sdg:{s1:45,s3:50,s4:58,s8:42,s107:50,s161:40,s163:38,s169:22},
    pathway:[{t:'Formal status determination',d:"Kuwait's Bidun registry is administered through Central Agency, not linked to UNHCR statelessness protection framework.",barriers:['No 1954 convention accession','Political sensitivity'],enablers:['Registry system exists','Centralized agency'],done:false},{t:'Documentation access',d:'Bidun affairs cards provide limited domestic functionality. No international travel documents issued.',barriers:['No travel document','International mobility blocked'],enablers:['Domestic ID card (limited)'],done:true},{t:'Local integration — de jure',d:'3+ generation Gulf-born Bidun have no naturalisation pathway. Integration is de facto, not de jure.',barriers:['Nationality law excludes Bidun','Political resistance'],enablers:['Social services access (partial)'],done:false},{t:'Naturalisation',d:'No formalised pathway. Kuwait proposed proxy Comoros passports rather than Kuwaiti citizenship.',barriers:['No political will','Proxy-citizenship scheme rejected'],enablers:[],done:false}]},
  roma:{label:'Roma',region:'Romania, Serbia, North Macedonia, Kosovo',origin:'Central/Eastern Europe',est:'~600,000 at risk in Europe',statelessYrs:20,ageRange:[16,50],riskLevel:'high',doc:'No birth certificate — administrative statelessness',housing:'Informal settlements on urban periphery',
    rights:{identity:55,travel:52,education:48,employment:38,healthcare:42,housing:32,legal:56,movement:70},
    risks:{duration:55,documentation:65,confinement:15,childStateless:72,genderDisc:58,exploitation:68},
    actions:[{s:'p',t:'Resolve statelessness situation',d:'EU Roma Integration Strategies exist; implementation varies significantly by member state.'},{s:'p',t:'No child born stateless',d:'Birth registration campaigns improving; undocumented births persist in informal settlements.'},{s:'p',t:'Protection status granted',d:'EU citizenship applies where nationality is confirmed; de facto stateless Roma fall through gaps.'},{s:'c',t:'Remove gender discrimination',d:'European states have gender-neutral nationality laws. Administrative barriers remain in practice.'},{s:'p',t:'Prevent statelessness via succession',d:'Post-Yugoslav succession created many stateless Roma; some regularised under succession laws.'},{s:'p',t:'Birth registration for all',d:'UNICEF and UNHCR mobile registration units operating in Kosovo and Serbia.'},{s:'p',t:'Regularise stateless migrants',d:'Regularisation programmes exist in Serbia and North Macedonia; coverage incomplete.'},{s:'p',t:'Issue nationality documentation',d:'Courts have granted nationality in some cases; bureaucratic barriers remain high.'},{s:'c',t:'Accede to UN conventions',d:'Most EU and Balkan states are parties to 1954 and/or 1961 conventions.'},{s:'p',t:'Improve statelessness data',d:'FRA and UNHCR data improving; significant structural undercounting remains.'}],
    sdg:{s1:48,s3:52,s4:50,s8:40,s107:58,s161:52,s163:55,s169:45},
    pathway:[{t:'Statelessness determination',d:'Formal SSD procedures exist in Balkan states; in practice few Roma access them due to awareness and cost barriers.',barriers:['Legal aid gaps','Administrative costs','Lack of awareness'],enablers:['UNHCR SSD support','EU funding'],done:false},{t:'Birth registration',d:'Children of unregistered parents face compound barriers. Several states allow late registration via court order.',barriers:['Parents unregistered','Informal births','No fixed address required'],enablers:['Mobile registration units','Court-ordered registration'],done:false},{t:'Status regularisation',d:'Multiple countries have legalization programmes; success rates vary by national law and political environment.',barriers:['Discrimination in application','No fixed address'],enablers:['NGO legal aid','EU monitoring pressure'],done:false},{t:'Nationality confirmation',d:'For stateless Roma born in successor states, nationality may be confirmed via court or administrative process.',barriers:['Lengthy court process','Document fees'],enablers:['Legal precedent exists','Ombudsman intervention'],done:false}]},
  nubian:{label:'Nubian-Kenyan',region:'Kibera, Nairobi & Northern Kenya',origin:'Kenya–Sudan border region',est:'~100,000 in Kenya',statelessYrs:25,ageRange:[18,55],riskLevel:'high',doc:'Kenyan birth cert refused; vetting system blocks ID',housing:'Kibera informal settlement, Nairobi',
    rights:{identity:40,travel:35,education:52,employment:45,healthcare:48,housing:55,legal:42,movement:60},
    risks:{duration:60,documentation:70,confinement:10,childStateless:65,genderDisc:55,exploitation:58},
    actions:[{s:'p',t:'Resolve statelessness situation',d:'2012 Kenyan Supreme Court (Nubian Community case) affirmed citizenship rights. Implementation remains slow.'},{s:'p',t:'No child born stateless',d:'Vetting system creates a generational trap. Some improvements post-2017 reforms.'},{s:'c',t:'Protection status granted',d:'Nubians are Kenyans by birth — the law affirms this. Recognition and enforcement are the barriers.'},{s:'c',t:'Remove gender discrimination',d:"Kenya's 2010 Constitution removes gender discrimination from nationality law."},{s:'n',t:'Prevent statelessness via succession',d:'Nubian statelessness stems from colonial-era exclusion, not recent state succession.'},{s:'p',t:'Birth registration for all',d:'General birth registration improving in Kenya; discriminatory vetting still blocks Nubian registration.'},{s:'p',t:'Regularise stateless migrants',d:'Nubians are not migrants — but are treated as such by the government vetting process.'},{s:'p',t:'Issue nationality documentation',d:'Post-court victory, some IDs issued; vetting system still blocks many applicants.'},{s:'p',t:'Accede to UN conventions',d:'Kenya acceded to the 1954 Convention in 2016; implementation framework still being developed.'},{s:'p',t:'Improve statelessness data',d:'UNHCR and Open Society Justice Initiative have produced profiles; no government data available.'}],
    sdg:{s1:50,s3:52,s4:55,s8:48,s107:55,s161:50,s163:48,s169:38},
    pathway:[{t:'Legal recognition as citizens',d:'Courts affirm Nubian Kenyans are citizens by birth. Implementation of rulings remains incomplete 12+ years later.',barriers:['Government vetting system','Discriminatory administrative practice'],enablers:['Court precedent','Civil society advocacy'],done:false},{t:'Birth and civil registration',d:"National birth registration improving but discriminatory vetting continues to block access to Kenya's national ID.",barriers:['Vetting committees','Tribal prejudice','Documentation of parents required'],enablers:['2010 Constitution','UNHCR support'],done:false},{t:'National ID issuance',d:'The Kenyan national ID unlocks employment, banking, voting, and healthcare. Nubians are systematically delayed or denied.',barriers:['Discriminatory officers','Extra documentation demands'],enablers:['Advocacy by Nubian Rights Forum','Legal challenges'],done:false},{t:'Full rights realisation',d:'Once ID issued, systemic discrimination in employment and public services must also be addressed separately.',barriers:['Entrenched discrimination','Economic marginalisation'],enablers:['Constitutional rights framework'],done:false}]},
  haitian:{label:'Haitian-Dominican',region:'Dominican Republic',origin:'Dominican-born, Haitian descent',est:'~133,000 denaturalised',statelessYrs:15,ageRange:[18,60],riskLevel:'high',doc:'Dominican birth cert held; TC 168-13 stripped nationality',housing:'Batey settlements & urban periphery',
    rights:{identity:22,travel:15,education:45,employment:32,healthcare:38,housing:42,legal:18,movement:50},
    risks:{duration:55,documentation:85,confinement:12,childStateless:88,genderDisc:60,exploitation:72},
    actions:[{s:'n',t:'Resolve statelessness situation',d:'2013 Constitutional Court ruling TC 168-13 retroactively stripped nationality from Dominican-born persons of Haitian descent (1929–2010).'},{s:'n',t:'No child born stateless',d:'Children of denaturalised parents inherit statelessness. Normalisation Law 169-14 largely ineffective — under 15% uptake.'},{s:'n',t:'Protection status granted',d:'Dominican Republic denies statelessness exists. Affected persons treated as undocumented migrants.'},{s:'p',t:'Remove gender discrimination',d:'Gender-neutral laws; Haitian descent discrimination applies regardless of gender.'},{s:'n',t:'Prevent statelessness via succession',d:'Not a succession issue — retroactive denaturalisation by domestic judicial ruling.'},{s:'p',t:'Birth registration for all',d:'Law 169-14 created a registration track B; barriers resulted in fewer than 15% registering.'},{s:'n',t:'Regularise stateless migrants',d:'Affected persons are native-born Dominicans, not migrants. Treated as undocumented foreigners.'},{s:'p',t:'Issue nationality documentation',d:'Some documents issued under 169-14 track B; citizenship restoration blocked.'},{s:'n',t:'Accede to UN conventions',d:'Dominican Republic not party to 1954 or 1961 statelessness conventions.'},{s:'p',t:'Improve statelessness data',d:'UNHCR, OSF, and OBMICA have profiled the population; government disputes all figures.'}],
    sdg:{s1:35,s3:40,s4:48,s8:32,s107:35,s161:28,s163:20,s169:10},
    pathway:[{t:'Challenge TC 168-13 ruling',d:'IACHR has found the ruling violates the American Convention. The Dominican Republic has not complied with remediation orders.',barriers:['State non-compliance','Nationalist political climate'],enablers:['IACHR ruling in favour','International pressure'],done:false},{t:'Naturalisation under Law 169-14',d:"Track B provides a naturalisation pathway — not restoration of original nationality. Bureaucratic barriers are severe.",barriers:['Requires documents the state stripped','Application window closed','Corruption in process'],enablers:['Law 169-14 formally exists'],done:false},{t:'Haitian nationality acquisition',d:"Some affected persons may have claim to Haitian nationality, but many have no ties to Haiti and Haiti's own documentation is fragile.",barriers:['Haiti documentation crisis','Born in DR with no Haitian ties'],enablers:['Haitian consular outreach programme'],done:false},{t:'International accountability',d:'CARICOM and IACHR pushing for Dominican compliance. No binding enforcement mechanism at regional level.',barriers:['Sovereignty argument','Political backlash in DR'],enablers:['Regional solidarity','UN Human Rights Council pressure'],done:false}]},
  fsu:{label:'Post-Soviet stateless',region:'Estonia, Latvia, Turkmenistan, Uzbekistan',origin:'Former Soviet Union',est:'~580,000 across FSU states',statelessYrs:30,ageRange:[25,70],riskLevel:'moderate',doc:'Alien passport (Estonia/Latvia) or no document',housing:'Urban — Soviet-era residential areas',
    rights:{identity:62,travel:55,education:72,employment:65,healthcare:68,housing:70,legal:58,movement:72},
    risks:{duration:55,documentation:52,confinement:5,childStateless:55,genderDisc:40,exploitation:38},
    actions:[{s:'c',t:'Resolve statelessness situation',d:'Estonia and Latvia have non-citizen alien passport systems; naturalisation is possible but requires language tests.'},{s:'p',t:'No child born stateless',d:'Estonia (2020) and Latvia allow children of non-citizens to acquire citizenship at birth — older cohorts unaffected.'},{s:'p',t:'Protection status granted',d:'Non-citizen status provides social security and most rights, except voting and some public sector roles.'},{s:'c',t:'Remove gender discrimination',d:'All FSU successor states have gender-neutral nationality laws.'},{s:'p',t:'Prevent statelessness via succession',d:'Baltic states offered alien passports post-independence; some individuals in CIS states remain fully stateless.'},{s:'p',t:'Birth registration for all',d:'Strong civil registration in Baltic states; weaker in Central Asian FSU states.'},{s:'c',t:'Regularise stateless migrants',d:'Non-citizen residents have permanent residence rights in Estonia and Latvia.'},{s:'p',t:'Issue nationality documentation',d:'Alien passports issued; naturalisation path open but take-up low among older cohorts.'},{s:'c',t:'Accede to UN conventions',d:'Estonia and Latvia are parties to 1954 and 1961 conventions; Central Asian states have mixed adherence.'},{s:'c',t:'Improve statelessness data',d:'UNHCR data robust for Baltic states; Central Asian data improving through joint programmes.'}],
    sdg:{s1:65,s3:70,s4:75,s8:65,s107:68,s161:65,s163:62,s169:58},
    pathway:[{t:'Alien passport system',d:'Estonia and Latvia issue alien passports to stateless residents, providing international travel without full citizenship rights.',barriers:['Not accepted by all countries','No EU citizenship rights'],enablers:['Alien passport in place','Permanent residence rights'],done:true},{t:'Naturalisation',d:'Language proficiency test required. Many older Russian-speaking residents unable or unwilling to naturalise.',barriers:['Language test barrier','Historical grievance','Elderly cohort unable to meet test'],enablers:['Clear pathway exists','EU integration incentive'],done:false},{t:'Child citizenship at birth',d:'Children of non-citizens may now acquire citizenship at birth in Estonia and Latvia — a generational solution.',barriers:['Previous cohorts unresolved'],enablers:['Law amended (2020)','Children acquire citizenship'],done:true},{t:'Full citizenship for remaining cohort',d:'Remaining non-citizens may naturalise or retain alien passport status indefinitely. Numbers declining naturally.',barriers:['Political identity — some prefer non-citizen status','Limited incentive for elderly'],enablers:['EU rights available post-naturalisation'],done:false}]}
};

const RIGHTS_LABELS=['Identity docs','Travel docs','Education','Employment','Healthcare','Housing','Legal access','Movement'];
const RIGHTS_KEYS=['identity','travel','education','employment','healthcare','housing','legal','movement'];
const RIGHTS_ARTS={identity:'Art. 27',travel:'Art. 28',education:'Art. 22',employment:'Art. 17–19',healthcare:'Art. 24',housing:'Art. 21',legal:'Art. 16',movement:'Art. 26'};
const RIGHTS_COLORS={identity:'#378ADD',travel:'#7F77DD',education:'#1D9E75',employment:'#BA7517',healthcare:'#639922',housing:'#D85A30',legal:'#5DCAA5',movement:'#888780'};
const RISK_KEYS=['duration','documentation','confinement','childStateless','genderDisc','exploitation'];
const RISK_LABELS=['Years stateless (indexed)','Documentation burden','Physical confinement','Child statelessness risk','Gender discrimination','Exploitation risk'];
const NAMES={rohingya:{g:['Mohammed','Noor','Ibrahim','Rashida','Fatimah','Ayesha'],f:['Ullah','Islam','Hussain','Begum']},bidun:{g:['Khalil','Hassan','Yousef','Maryam','Layla','Noura'],f:['Al-Rashidi','Al-Mutairi','Al-Shammari']},roma:{g:['Mihai','Florin','Elena','Ana','Vasile','Maria'],f:['Cioabă','Nicolescu','Gheorghe']},nubian:{g:['Hassan','Omar','Ouma','Fatuma','Amira','Zainab'],f:['Osman','Ibrahim','Mohamed']},haitian:{g:['Jean-Pierre','Josué','Claudel','Marie','Céleste','Nadège'],f:['Pierre','Joseph','Baptiste']},fsu:{g:['Mikhail','Andrei','Sergei','Tatiana','Natalya','Olga'],f:['Ivanov','Petrov','Sokolov']}};

let radarChart = null;
function rnd(a){return a[Math.floor(Math.random()*a.length)];}
function rndN(mn,mx){return Math.floor(Math.random()*(mx-mn+1))+mn;}
function riskColor(v){return v>=80?'#E24B4A':v>=60?'#BA7517':v>=40?'#378ADD':'#1D9E75';}

function generateTwin(){
  const key=document.getElementById('popSel').value;
  const pop=POP[key];
  const ns=NAMES[key];
  const gn=rnd(ns.g),fn=rnd(ns.f);
  const age=rndN(pop.ageRange[0],pop.ageRange[1]);
  const sYrs=Math.min(age-4,rndN(5,Math.min(age-4,pop.statelessYrs+8)));
  const kids=rndN(0,5);
  const ini=gn[0]+fn[0];
  const rb={extreme:'b-r',high:'b-w',moderate:'b-i',low:'b-s'}[pop.riskLevel];
  const ri={extreme:'ti-flame',high:'ti-alert-triangle',moderate:'ti-info-circle',low:'ti-circle-check'}[pop.riskLevel];
  const tid='DT-'+key.toUpperCase().slice(0,3)+'-'+Math.floor(Math.random()*90000+10000);

  document.getElementById('personaDiv').innerHTML=`
    <div class="avt">${ini}</div>
    <p style="font-size:16px;font-weight:500;margin:0 0 2px">${gn} ${fn}</p>
    <p style="font-size:12px;color:var(--text-secondary);margin:0 0 8px">${pop.label} · age ${age}</p>
    <span class="badge ${rb}"><i class="ti ${ri}"></i>${pop.riskLevel} risk</span>
    <p class="mono" style="margin:9px 0 13px">Twin ID: ${tid}</p>
    <div>
      <div class="fr"><span class="fr-l">Origin</span><span class="fr-v">${pop.origin}</span></div>
      <div class="fr"><span class="fr-l">Location</span><span class="fr-v">${pop.region}</span></div>
      <div class="fr"><span class="fr-l">Stateless for</span><span class="fr-v">${sYrs} years</span></div>
      <div class="fr"><span class="fr-l">Population est.</span><span class="fr-v">${pop.est}</span></div>
      <div class="fr"><span class="fr-l">Documentation</span><span class="fr-v" style="font-size:11px">${pop.doc}</span></div>
      <div class="fr"><span class="fr-l">Residence</span><span class="fr-v" style="font-size:11px">${pop.housing}</span></div>
      <div class="fr"><span class="fr-l">Dependants</span><span class="fr-v">${kids} child${kids!==1?'ren':''}</span></div>
    </div>`;

  renderRights(pop); renderRisk(pop); renderPathway(pop,key); renderGoals(pop,key);
}

function renderRights(pop){
  const vals=RIGHTS_KEYS.map(k=>pop.rights[k]);
  const dark=matchMedia('(prefers-color-scheme: dark)').matches;
  if(radarChart){radarChart.destroy();radarChart=null;}
  const ctx=document.getElementById('radarChart').getContext('2d');
  radarChart=new Chart(ctx,{type:'radar',data:{labels:RIGHTS_LABELS,datasets:[
    {label:'Convention standard',data:[100,100,100,100,100,100,100,100],backgroundColor:dark?'rgba(55,138,221,0.06)':'rgba(55,138,221,0.07)',borderColor:'#378ADD',borderDash:[4,4],borderWidth:1.5,pointRadius:0},
    {label:'Current access',data:vals,backgroundColor:dark?'rgba(29,158,117,0.25)':'rgba(29,158,117,0.18)',borderColor:'#1D9E75',borderWidth:2,pointBackgroundColor:'#1D9E75',pointRadius:3}
  ]},options:{responsive:true,maintainAspectRatio:false,scales:{r:{min:0,max:100,ticks:{display:false},grid:{color:dark?'rgba(255,255,255,0.07)':'rgba(0,0,0,0.07)'},angleLines:{color:dark?'rgba(255,255,255,0.07)':'rgba(0,0,0,0.07)'},pointLabels:{font:{size:10},color:dark?'#9a9890':'#888780'}}},plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>` ${c.dataset.label}: ${c.parsed.r}%`}}}}});

  document.getElementById('rightsDetail').innerHTML=RIGHTS_KEYS.map(k=>`
    <div class="rbar">
      <div class="rbar-h"><span>${RIGHTS_ARTS[k]} — ${k.charAt(0).toUpperCase()+k.slice(1)}</span><span>${pop.rights[k]}%</span></div>
      <div class="rbar-bg"><div class="rbar-f" style="width:${pop.rights[k]}%;background:${RIGHTS_COLORS[k]}"></div></div>
    </div>`).join('');
}

function renderRisk(pop){
  const vals=RISK_KEYS.map(k=>pop.risks[k]);
  const comp=Math.round(vals.reduce((a,b)=>a+b,0)/vals.length);
  const rb={extreme:'b-r',high:'b-w',moderate:'b-i',low:'b-s'}[pop.riskLevel];
  const rlabel={extreme:'Extreme vulnerability',high:'High vulnerability',moderate:'Moderate vulnerability',low:'Low vulnerability'}[pop.riskLevel];
  document.getElementById('riskContent').innerHTML=`
    <div class="two-col">
      <div class="mc"><p class="mc-l">composite risk score</p><p class="mc-v">${comp}<span style="font-size:14px;color:var(--text-secondary)">/100</span></p></div>
      <div class="mc"><p class="mc-l">classification</p><p style="margin:6px 0 0"><span class="badge ${rb}">${rlabel}</span></p></div>
    </div>
    ${RISK_KEYS.map((k,i)=>`
    <div class="rbar">
      <div class="rbar-h"><span>${RISK_LABELS[i]}</span><span>${vals[i]}/100</span></div>
      <div class="rbar-bg"><div class="rbar-f" style="width:${vals[i]}%;background:${riskColor(vals[i])}"></div></div>
    </div>`).join('')}
    <p class="info-note">Composite methodology based on UNHCR vulnerability assessment framework. Scores use proxy data from UNHCR statistical reports, statelessness duration, legal exposure, and documentation burden indices.</p>`;
}

function renderPathway(pop,key){
  document.getElementById('pathwayContent').innerHTML=pop.pathway.map((step,i)=>{
    const last=i===pop.pathway.length-1;
    const dc=step.done?'#1D9E75':'var(--border-md)';
    const bg=step.done?'rgba(29,158,117,0.1)':'transparent';
    const tc=step.done?'#1D9E75':'var(--text-secondary)';
    const sb=step.done?'<span class="badge b-s" style="font-size:10px">achieved</span>':'<span class="badge b-r" style="font-size:10px">blocked</span>';
    return `<div class="ps">
      <div class="si-col">
        <div class="s-circ" style="border-color:${dc};background:${bg};color:${tc}">${step.done?'✓':i+1}</div>
        ${last?'':'<div class="s-line"></div>'}
      </div>
      <div class="sk">
        <p class="sk-t">${step.t} ${sb}</p>
        <p class="sk-d">${step.d}</p>
        ${step.barriers.map(b=>`<span class="tag tag-r">✕ ${b}</span>`).join('')}
        ${step.enablers.map(e=>`<span class="tag tag-g">✓ ${e}</span>`).join('')}
      </div>
    </div>`;
  }).join('')+`<p class="info-note">UNHCR identifies three durable solutions: voluntary return, local integration, third-country resettlement. For stateless persons, nationality acquisition is a fourth requirement not applicable to refugees.</p>`;
}

function renderGoals(pop){
  document.getElementById('unhcrActions').innerHTML=pop.actions.map((a,i)=>`
    <div class="ai">
      <div class="ai-n ${a.s==='c'?'n-c':a.s==='p'?'n-p':'n-n'}">${a.s==='c'?'✓':a.s==='p'?'~':i+1}</div>
      <div><p class="ai-t">${i+1}. ${a.t}</p><p class="ai-d">${a.d}</p></div>
    </div>`).join('');

  const sdgItems=[
    {k:'s1',num:'SDG 1.3',t:'Social protection',color:'#BA7517'},{k:'s3',num:'SDG 3.8',t:'Health coverage',color:'#639922'},
    {k:'s4',num:'SDG 4.1',t:'Quality education',color:'#1D9E75'},{k:'s8',num:'SDG 8.5',t:'Decent work',color:'#378ADD'},
    {k:'s107',num:'SDG 10.7',t:'Safe migration',color:'#5DCAA5'},{k:'s161',num:'SDG 16.1',t:'Reduce violence',color:'#7F77DD'},
    {k:'s163',num:'SDG 16.3',t:'Rule of law',color:'#D85A30'},{k:'s169',num:'SDG 16.9',t:'Legal identity',color:'#E24B4A'}
  ];
  document.getElementById('sdgGrid').innerHTML=`<div class="sg">${sdgItems.map(s=>`
    <div class="sc-c"><p class="sc-n">${s.num}</p><p class="sc-t">${s.t}</p>
    <div class="sc-b"><div class="sc-f" style="width:${pop.sdg[s.k]}%;background:${s.color}"></div></div>
    <p class="sc-p">${pop.sdg[s.k]}% achieved</p></div>`).join('')}</div>
  <p class="info-note">SDG scores are proxy estimates based on UNHCR annual reports, country UPR submissions, and statelessness research by OSJI, Tilburg University Institute on Statelessness and Inclusion, and ENS.</p>`;
}

function switchTab(id,btn){
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('on'));
  document.querySelectorAll('.pane').forEach(p=>p.classList.remove('on'));
  btn.classList.add('on');
  document.getElementById(id).classList.add('on');
}

generateTwin();
</script>
</body>
</html>
