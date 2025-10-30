---


---

<h1 id="introduction">Introduction</h1>
<p>This is a template to collect information of every use case. The example used is the famous “Hello World”. For that I have to make a disclaimer:</p>
<p>It is an illustrative instance-level example of a class-level model that defines entities, attributes, and relations. The Hello World example is a simplified illustration used to explain class-attribute-relation modeling concepts. “Hello” and “World” represent example entities or classes, not literal data instances.</p>
<p>If you are so inclined, you can refactor it to an instance of the conceptual model. For instance:</p>
<pre><code>Classes:  Greeting and Audience.
Relation:  Greeting greets Audience.
Instances:  Hello (instance of Greeting).
World (instance of Audience).
Statement:  Hello greets World.
</code></pre>
<h1 id="use-case-overview-of-hello-world">Use Case Overview of Hello World</h1>
<p>Purpose: Capture the story and high-level purpose of the use case “Hello World”.</p>
<h2 id="storyline">Storyline</h2>
<p>What is the scenario being solved? A fictional organization, Hello Authority, issues a simple attestation to a holder’s digital wallet.</p>
<p>This attestation confirms that Hello (the issuer entity) has a valid and verifiable connection with World (the subject entity).</p>
<p>The attestation’s only statement is:</p>
<p>“Hello greets World.”</p>
<h2 id="business-context--motivation">Business Context / Motivation</h2>
<p>Why is this attestation needed?</p>
<p>The  <em>Hello World</em>  use case serves as a minimal, example to demonstrate how an attestation can represent structured information - including entities, attributes, relations, and lifecycle behaviors - within the EU wallet ecosystem (and beyond).</p>
<p>It helps modelers, developers, and policy stakeholders understand how semantics, trust, and lifecycle interact when designing and exchanging digital attestations.</p>
<h2 id="stakeholders">Stakeholders</h2>
<p>issuer,<br>
holder,<br>
verifier,<br>
relying party,<br>
etc.</p>
<h2 id="expected-outcome">Expected Outcome</h2>
<p>What should happen when the attestation is used? By the end of the Hello World example, users of the template should understand:</p>
<ol>
<li>
<p>How to describe an attestation using structured semantic elements (classes, attributes, relations).</p>
</li>
<li>
<p>If and if so how those elements are linked to trust, lifecycle, and interoperability concerns.</p>
</li>
<li>
<p>How to extend this structure to real-world use cases, e.g., ID, IBAN, or EUCC.</p>
</li>
</ol>
<h3 id="meta-purpose">Meta-purpose</h3>
<p>The Hello World attestation is not about greeting the world - it’s about greeting the conceptual structure of attestations themselves. It provides a safe sandbox to explore what it means to model meaning.</p>
<h1 id="data-model-or-knowledge-graph">Data Model or Knowledge Graph</h1>
<p>Purpose: Capture the entities, attributes, and relationships.</p>
<p>The Hello World data model is depicted below. It is a simple model to illustrate the use of data models to capture the use case entities.</p>
<p><img src="https://www.plantuml.com/plantuml/png/bL91ozD04BtlhnZwtPGMX7f9GMfLy20UH2YUPCrEax6xCsLsGWp5_-vkcw35Y-QKztRVUpEFtMVpQaEApiWYmdkCKM0KZS6vDlgSP-hgu5cdY4RSVSOV1itzmC7pW2TYCX8kv787nXuPa5iPs50haoMXC2v66HhtSmavriHRI93aYJ_wXCKDlLfV8dnNqNRpSWk9udUleP2jf8HiC_-DOgmZJ4MJWKumoG13HiYzg45kVSJVUU_OoAPROF8Sl8bEnL8kTGqVwyNRUaqppxfwiOArKjVR-bK1cmslvg6V8Z4sRxsUFs7OMUccEVPa2CtN-ZtM-FIXMdof_-FkR-4C7ahvBycyrpzgN4y1eILj8pgNpyGNhpx1tUlg3huzToe3XpSIHU4FL_TQLSOxlTWTH0Fg8rVVoW9ggtlaK9_RBm00" alt="Hello World Data "><br>
Figure 1 “Hello World” exaple diagram or knoledge graph.</p>
<pre class=" language-mermaid"><svg id="mermaid-svg-R6OzE7aSaTXv0mqF" width="100%" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" height="205.28125" style="max-width: 143.90625px;" viewBox="-20 -20 143.90625 205.28125"><style>#mermaid-svg-R6OzE7aSaTXv0mqF{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}#mermaid-svg-R6OzE7aSaTXv0mqF .error-icon{fill:#552222;}#mermaid-svg-R6OzE7aSaTXv0mqF .error-text{fill:#552222;stroke:#552222;}#mermaid-svg-R6OzE7aSaTXv0mqF .edge-thickness-normal{stroke-width:2px;}#mermaid-svg-R6OzE7aSaTXv0mqF .edge-thickness-thick{stroke-width:3.5px;}#mermaid-svg-R6OzE7aSaTXv0mqF .edge-pattern-solid{stroke-dasharray:0;}#mermaid-svg-R6OzE7aSaTXv0mqF .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-svg-R6OzE7aSaTXv0mqF .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-svg-R6OzE7aSaTXv0mqF .marker{fill:#666;stroke:#666;}#mermaid-svg-R6OzE7aSaTXv0mqF .marker.cross{stroke:#666;}#mermaid-svg-R6OzE7aSaTXv0mqF svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-svg-R6OzE7aSaTXv0mqF g.classGroup text{fill:#999;fill:#111111;stroke:none;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:10px;}#mermaid-svg-R6OzE7aSaTXv0mqF g.classGroup text .title{font-weight:bolder;}#mermaid-svg-R6OzE7aSaTXv0mqF .classTitle{font-weight:bolder;}#mermaid-svg-R6OzE7aSaTXv0mqF .node rect,#mermaid-svg-R6OzE7aSaTXv0mqF .node circle,#mermaid-svg-R6OzE7aSaTXv0mqF .node ellipse,#mermaid-svg-R6OzE7aSaTXv0mqF .node polygon,#mermaid-svg-R6OzE7aSaTXv0mqF .node path{fill:#eee;stroke:#999;stroke-width:1px;}#mermaid-svg-R6OzE7aSaTXv0mqF .divider{stroke:#999;stroke:1;}#mermaid-svg-R6OzE7aSaTXv0mqF g.clickable{cursor:pointer;}#mermaid-svg-R6OzE7aSaTXv0mqF g.classGroup rect{fill:#eee;stroke:#999;}#mermaid-svg-R6OzE7aSaTXv0mqF g.classGroup line{stroke:#999;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF .classLabel .box{stroke:none;stroke-width:0;fill:#eee;opacity:0.5;}#mermaid-svg-R6OzE7aSaTXv0mqF .classLabel .label{fill:#999;font-size:10px;}#mermaid-svg-R6OzE7aSaTXv0mqF .relation{stroke:#666;stroke-width:1;fill:none;}#mermaid-svg-R6OzE7aSaTXv0mqF .dashed-line{stroke-dasharray:3;}#mermaid-svg-R6OzE7aSaTXv0mqF #compositionStart,#mermaid-svg-R6OzE7aSaTXv0mqF .composition{fill:#666 !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #compositionEnd,#mermaid-svg-R6OzE7aSaTXv0mqF .composition{fill:#666 !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #dependencyStart,#mermaid-svg-R6OzE7aSaTXv0mqF .dependency{fill:#666 !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #dependencyStart,#mermaid-svg-R6OzE7aSaTXv0mqF .dependency{fill:#666 !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #extensionStart,#mermaid-svg-R6OzE7aSaTXv0mqF .extension{fill:#666 !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #extensionEnd,#mermaid-svg-R6OzE7aSaTXv0mqF .extension{fill:#666 !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #aggregationStart,#mermaid-svg-R6OzE7aSaTXv0mqF .aggregation{fill:#eee !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF #aggregationEnd,#mermaid-svg-R6OzE7aSaTXv0mqF .aggregation{fill:#eee !important;stroke:#666 !important;stroke-width:1;}#mermaid-svg-R6OzE7aSaTXv0mqF .edgeTerminals{font-size:11px;}#mermaid-svg-R6OzE7aSaTXv0mqF:root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}#mermaid-svg-R6OzE7aSaTXv0mqF class{fill:apa;}</style><g></g><defs><marker id="extensionStart" class="extension" refX="0" refY="7" markerWidth="190" markerHeight="240" orient="auto"><path d="M 1,7 L18,13 V 1 Z"></path></marker></defs><defs><marker id="extensionEnd" refX="19" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 1,1 V 13 L18,7 Z"></path></marker></defs><defs><marker id="compositionStart" class="extension" refX="0" refY="7" markerWidth="190" markerHeight="240" orient="auto"><path d="M 18,7 L9,13 L1,7 L9,1 Z"></path></marker></defs><defs><marker id="compositionEnd" refX="19" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L1,7 L9,1 Z"></path></marker></defs><defs><marker id="aggregationStart" class="extension" refX="0" refY="7" markerWidth="190" markerHeight="240" orient="auto"><path d="M 18,7 L9,13 L1,7 L9,1 Z"></path></marker></defs><defs><marker id="aggregationEnd" refX="19" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L1,7 L9,1 Z"></path></marker></defs><defs><marker id="dependencyStart" class="extension" refX="0" refY="7" markerWidth="190" markerHeight="240" orient="auto"><path d="M 5,7 L9,13 L1,7 L9,1 Z"></path></marker></defs><defs><marker id="dependencyEnd" refX="19" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L14,7 L9,1 Z"></path></marker></defs><g id="classid-Hello-52" class="classGroup" transform="translate(0.8046875,0 )"><rect x="0" y="0" width="102.296875" height="52.640625" class=" "></rect><text y="15" x="0"><tspan class="title" x="39.078125">Hello</tspan></text><line x1="0" y1="21.625" y2="21.625" x2="102.296875"></line><text x="5" y="31.625" fill="white" class="classText"><tspan x="5">greetingText: Hello</tspan><tspan x="5" dy="10">greeting when</tspan></text><line x1="0" y1="48.25" y2="48.25" x2="102.296875"></line><text x="5" y="63.25" fill="white" class="classText"></text></g><g id="classid-World-53" class="classGroup" transform="translate(0,102.640625 )"><rect x="0" y="0" width="103.90625" height="62.640625" class=" "></rect><text y="15" x="0"><tspan class="title" x="38.1875">World</tspan></text><line x1="0" y1="21.625" y2="21.625" x2="103.90625"></line><text x="5" y="31.625" fill="white" class="classText"><tspan x="5">domainName: earth</tspan><tspan x="5" dy="10">54 miljard</tspan><tspan x="5" dy="10">54 billion</tspan></text><line x1="0" y1="58.25" y2="58.25" x2="103.90625"></line><text x="5" y="73.25" fill="white" class="classText"></text></g><path d="M51.953125,52.640625L51.953125,56.807291666666664C51.953125,60.973958333333336,51.953125,69.30729166666667,51.953125,77.640625C51.953125,85.97395833333333,51.953125,94.30729166666667,51.953125,98.47395833333333L51.953125,102.640625" id="edge14" class="relation" marker-end="url(#dependencyEnd)"></path><g class="classLabel"><rect class="box" x="34.65625" y="65.75" width="34.59375" height="16.625"></rect><text class="label" x="51.953125" y="77.640625" fill="red" text-anchor="middle">Greets</text></g><g class="cardinality"><text class="type1" x="46.953125" y="65.140625" fill="black" font-size="6">1</text></g><g class="cardinality"><text class="type2" x="61.953125" y="90.140625" fill="black" font-size="6">1..n</text></g></svg></pre>
<p><strong>Entity: Hello</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Description/Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>Hello</td>
<td>Represents the  <em>Hello</em>  part of  <em>Hello World</em>. It symbolizes the entity initiating a greeting.</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Attribute</th>
<th>Description</th>
<th>mandatory</th>
<th>private</th>
<th>datatype</th>
</tr>
</thead>
<tbody>
<tr>
<td>greetingText</td>
<td>An example of a mandatory attribute that holds the text of the greeting.</td>
<td>yes</td>
<td>no</td>
<td>string</td>
</tr>
<tr>
<td>definition</td>
<td>An example of an optional, private attribute describing the greeting or its context.</td>
<td>no</td>
<td>yes</td>
<td>string</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Relation</th>
<th>Description</th>
<th>Left Entity</th>
<th>Right Entity</th>
<th>Left Role</th>
<th>Right Role</th>
<th>Cardinality</th>
<th>Optional</th>
</tr>
</thead>
<tbody>
<tr>
<td>greets</td>
<td>Expresses the relation between Hello (the greeter) and World (the greeted).</td>
<td>Hello</td>
<td>World</td>
<td>greeter</td>
<td>greeted</td>
<td>1 1…n</td>
<td>no</td>
</tr>
</tbody>
</table><blockquote>
<p>Questions to ask per relation:<br>
Check whether the direction (Hello ? World) reflects the dominant<br>
flow of meaning.<br>
If both sides can have multiple relations (n?n), consider<br>
refactoring the relationship into a separate class (e.g.,<br>
GreetingEvent)</p>
</blockquote>
<p><strong>Entity: World</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Description/Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>World</td>
<td>Represents the  <em>World</em>  part of  <em>Hello World</em>. It symbolizes the entity initiating a greeting.</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Attribute</th>
<th>Description</th>
<th>mandatory</th>
<th>private</th>
<th>datatype</th>
</tr>
</thead>
<tbody>
<tr>
<td>domainName</td>
<td>A mandatory attribute representing the domain, context, or scope being greeted.</td>
<td>yes</td>
<td>no</td>
<td>string</td>
</tr>
<tr>
<td>age</td>
<td>An optional, private attribute showing example metadata about the World.</td>
<td>no</td>
<td>yes</td>
<td>string</td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Relation</th>
<th>Description</th>
<th>Left Entity</th>
<th>Right Entity</th>
<th>Left Role</th>
<th>Right Role</th>
<th>Cardinality</th>
<th>Optional</th>
</tr>
</thead>
<tbody>
<tr>
<td>(none)</td>
<td>The World entity has no outgoing relations in this example.</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
<td>-</td>
</tr>
</tbody>
</table><h1 id="workflow-of-the-attestation">Workflow of the Attestation</h1>
<p>Purpose: Map the flow of actions, data, and interactions between entities.</p>

<table>
<thead>
<tr>
<th>Actor</th>
<th>Role</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Hello Authority</td>
<td>issuer</td>
<td>The trusted party that creates and issues the Hello World attestation. It defines the semantics, attributes, and relation (“greets”) between the entities Hello and World. It also manages issuance, signing, and potential revocation.</td>
</tr>
<tr>
<td>Wallet Owner</td>
<td>holder</td>
<td>The user (or test persona) who receives the Hello World attestation in their EU Digital Identity Wallet. The holder stores, manages, and can present the attestation when needed.</td>
</tr>
<tr>
<td>EU business Wallet</td>
<td>Wallet</td>
<td>The technical component used by the holder to receive, store, and present the attestation. It handles workflow and format negotiation (JSON-LD, SD-JWT, mDoc) and enforces binding with the holder’s ID attestation.</td>
</tr>
<tr>
<td>Verifier</td>
<td>relying party</td>
<td>The entity that requests and verifies the Hello World attestation to confirm the claim “Hello greets World” is valid and trustworthy. It validates the signature, the wallet binding, and the issuer’s trust status.</td>
</tr>
<tr>
<td>Trust Registry</td>
<td>governance authority</td>
<td>Maintains the trust list or framework under which the Hello World issuer (Hello Authority) is recognized as trustworthy. It ensures that the attestation can be verified across systems and jurisdictions.</td>
</tr>
<tr>
<td>Attestation Registry</td>
<td>registry</td>
<td>Stores or indexes attestations for verification (if used in your architecture).</td>
</tr>
<tr>
<td>Revocation Service</td>
<td>revocation service</td>
<td>Manages lifecycle events, such as the deactivation of the Hello World attestation.</td>
</tr>
</tbody>
</table><p>Trigger Event: What initiates the workflow? a request from the holder’s wallet to obtain the “Hello World” attestation from the Hello Authority.</p>
<p>Post-condition: What is the result of the workflow? The holder’s wallet contains an active, verifiable Hello World attestation bound to the ID attestation.</p>
<p>See Figure 2 for a simplified overview.</p>
<p><img src="https://www.plantuml.com/plantuml/png/ZLJDaXet4BxhAReuh6SgIt6VpO-niIjR5SSkMDkLAYvQgHaKX3HfQMP2Ggho3dd3F4ca4R0C2snEZAJkhx_kxsjUEy_9rslDlF8QOV0ZQctXgoKjOUmzXdUlh85___u7tXavz7OOVcB0Qg5jEs3i5RorsX98N2YZOh23H-vGGaZRs9f0QEuSICLBucl6t4gPYeTFuCAhHlaD_Ca0tbYII0bhmcarHHbktrlZJ-_USB4goTP6ffUVLBdqlqJYBVlh2DvOZm7wQiB_Bzo3TgrQQsxm2lE7ED2hbLD8B7GsDy5Uvi29RDiHE8q9cdns-3JUEFfZrWwo0E6JM3aqYiDsBBobBJngArOk07HdLy0Crznu9U23bQYHRY5PP5pxfQM8djqxLoFbuSLg6ICcgbIUQ_ZAjKP_2r-Gr4B5bmUgdOSfbifvsepU1rRO1Y_TXhl6YkIr6LAZ1Dxs3BZFWSnMyOBhdB5jgWYZNIdus1gaBUjSpOe7KcM9L8Jat-g0D3V7_Xu0VyA_2s1zsbjMl5sYM46Re6_cvdu23TTAXgxlc5f0zYMUViZ1Bz50zgs8EXGx7RxVeCiPQeVFNepDMJ55W-tSF252e6qhXaQgHNXEb7VJBWdHkyGxKhsaGI3TSU8UWHB27Ii-4GQziTzlCLEbERwQcnjmw24UQmVVGOVPbNikJYXq7xSz5Fi3zoc4mfASc-m0COuMn3nYd1Cpe7pSgQatGDqjKe_dzMOdg0C-WUgelYZep5l2qwYzEo6RejueKy8dJduJuVSYL8GEpNvCcLt0uBakW_oyYQo9kV0D24BkiGUMn8d7cDkhVoob2rA5YHB23OGB3kkuZ36blr0mWiDATVITrGscwH3u67j9pcJslP9P4cuK8rSeHtFpxlTAKVYQrHMIGuaoFqFvi1Gm_dcoK__gVW0KOo6myZrLBgyDGEZgLnGdyMbfs2iO3eTmr5x5_H8opQEhi47ZynXnrLAfvJxy-Obzhf8uUxFlXdNM1LCKg9f3i5XoK-BTt7m8lKLZI3HncU3Uy6veBnXpLZ-ww4tZGKJT72ouqj1q6MB7ElsVl4OZwxN-3m00" alt="Swimlane 1"><br>
Figure 2 The swim lane diagram Hello World issuance and revocation.</p>
<p>Notable Interactions / Dependencies: Are there cross-border or cross-domain steps?</p>
<h1 id="life-cycle-of-the-attestation">Life Cycle of the Attestation</h1>
<p>Purpose: Capture how the attestation evolves over time.</p>

<table>
<thead>
<tr>
<th>Stage</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Creation / Issuance</td>
<td>Who issues it and under what conditions? The Hello Authority (trusted issuing entity). Preconditions: The holder’s wallet is activated and bound to a valid ID.</td>
</tr>
<tr>
<td>Usage / Presentation</td>
<td>How and where it’s presented? The attestation may be presented to any Verifier who requests proof that the Hello Authority issued a valid greeting (symbolically representing any verifiable claim). The wallet creates a verifiable presentation (potentially with selective disclosure).</td>
</tr>
<tr>
<td>Update / Renewal</td>
<td>Can it change or expire? The Hello World attestation is static by design - it has no mutable attributes. However, if either the schema changes or the Hello Authority updates its signing keys or trust policy, then a new version of the attestation must be issued. Optionally, an expiry date can be set to force periodic renewal for testing lifecycle behavior.</td>
</tr>
<tr>
<td>Revocation / Expiry</td>
<td>How is it invalidated or replaced? The Hello World attestation can be revoked by the issuer or automatically expire after a predefined validity period.</td>
</tr>
<tr>
<td>Archiving / End-of-life Handling</td>
<td>What happens after expiry or revocation? The wallet may retain a cryptographic proof of the attestation (hash or record) for audit or traceability purposes, while marking it as expired or revoked. The issuer may archive metadata (e.g., issuance date, revocation timestamp, format used) for audit trails, compliance testing, or statistical reporting complying to privacy rules. In demonstrative settings, archived attestations can serve as test material for verifying lifecycle management and revocation interoperability.</td>
</tr>
</tbody>
</table><h1 id="requirements-and-constraints">Requirements and Constraints</h1>
<p>Purpose: Capture explicit and implicit technical or policy requirements.</p>
<h2 id="information-requirements">Information requirements</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Requirement</th>
<th>Source</th>
<th>Verification method</th>
</tr>
</thead>
<tbody>
<tr>
<td>I001</td>
<td>The  <em>Hello World</em>  attestation shall serve as an illustrative reference implementation to clarify the intended use of this template and to demonstrate practical dilemmas and opportunities arising at the intersection of semantics, trust, lifecycle management, and real-world usage. While not intended as a production-grade attestation, it should support analysis and discussion of how these dimensions interact within the broader EU wallet ecosystem.</td>
<td>Bart Bink</td>
<td>inspect</td>
</tr>
</tbody>
</table><h2 id="legal-and-regulatory-requirements">Legal and Regulatory requirements</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Requirement</th>
<th>Source</th>
<th>Verification method</th>
</tr>
</thead>
<tbody>
<tr>
<td>L001</td>
<td>The Hello World attestation is currently outside the scope of eIDAS2 compliance requirements. However, its design should not preclude future alignment with eIDAS2 trust frameworks, credential formats, or conformity assessment procedures.</td>
<td>eIDAS2</td>
<td>review</td>
</tr>
</tbody>
</table><h2 id="functional-requirements">Functional requirements</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Requirement</th>
<th>Source</th>
<th>Verification method</th>
</tr>
</thead>
<tbody>
<tr>
<td>F001</td>
<td>The Hello World attestation shall be capable of being issued to any compliant digital wallet, irrespective of the wallet provider or implementation, provided that the wallet supports at least one of the supported attestation formats (JSON-LD, SD-JWT, or mDoc). The attestation should not rely on wallet-specific extensions or proprietary interfaces that would limit its interoperability.</td>
<td>Bart Bink</td>
<td>test</td>
</tr>
</tbody>
</table><h2 id="technical-requirements-–-e.g.-security-privacy-performance-usability.">Technical requirements – e.g. security, privacy, performance, usability.</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Requirement</th>
<th>Source</th>
<th>Verification method</th>
</tr>
</thead>
<tbody>
<tr>
<td>T001</td>
<td>The issuer MUST issue the Hello World attestation as a JSON-LD-based attestation. If the recipient wallet does not support JSON-LD, the issuer MUST fall back to an SD-JWT-based attestation. If the recipient wallet does not support SD-JWT, the issuer MUST issue the attestation as an mDoc.</td>
<td>WEBUILD Semantic Modeling interoperability requirement.</td>
<td>test</td>
</tr>
</tbody>
</table><h2 id="operational-requirements">Operational requirements</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Requirement</th>
<th>Source</th>
<th>Verification method</th>
</tr>
</thead>
<tbody>
<tr>
<td>O001</td>
<td>The  <em>Hello World</em>  attestation shall be automatically reactivated/reissued whenever the user’s associated digital identity attestation is renewed or replaced, in order to maintain a valid binding between the attestation and the user’s active eWallet identity. If the recipient wallet does not support SD-JWT, the issuer MUST issue the attestation as an mDoc.</td>
<td>WEBUILD Semantic Modeling interoperability requirement.</td>
<td>test</td>
</tr>
</tbody>
</table><h2 id="governance-and-trust-restrictions">Governance and trust restrictions</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Requirement</th>
<th>Source</th>
<th>Verification method</th>
</tr>
</thead>
<tbody>
<tr>
<td>G001</td>
<td>The  <em>Hello World</em>  attestation shall be cryptographically bound to both the holder’s eWallet and the holder’s verified identity attestation to ensure authenticity and non-transferability.</td>
<td>General trust mechanism.</td>
<td>review</td>
</tr>
</tbody>
</table><h2 id="open-questions--gaps-–-for-follow-up-or-design-iterations.">Open Questions / Gaps – For follow-up or design iterations.</h2>

<table>
<thead>
<tr>
<th>No.</th>
<th>Question</th>
<th>Why</th>
</tr>
</thead>
<tbody>
<tr>
<td>Q001</td>
<td>How should the  <em>Hello World</em>  attestation’s semantics — including its entities, attributes, and relationships — be aligned with existing vocabularies or ontologies to ensure that other ecosystems or wallet implementations can interpret its meaning consistently?</td>
<td>Where does the authoritative meaning of each attribute come from, and how stable must that be?</td>
</tr>
<tr>
<td>Q002</td>
<td>Which core entities and attributes in the  <em>Hello World</em>  attestation should be represented as references to existing EU or W3C vocabularies, and which—if any—require the definition of new, domain-specific terms?</td>
<td><strong>Information model:</strong> <em>semantic reuse vs. semantic innovation,</em> ensuring interoperability while avoiding redundancy.</td>
</tr>
<tr>
<td>Q003</td>
<td>How can we semantically represent the lifecycle states of the  <em>Hello World</em> attestation (e.g., issued, active, revoked, superseded) so that they are machine-interpretable and consistent across issuers and verifiers?</td>
<td><strong>Lyfe Cycle:</strong> <em>Lifecycle concepts are often procedural in code</em> but implicit in meaning. Defining them semantically enables automation, policy reasoning, and consistent interpretation across ecosystems (outside of the eWallet ecosystem too).</td>
</tr>
<tr>
<td>Q004</td>
<td>What is the most appropriate way to semantically express the binding between the  <em>Hello World</em>  attestation, the holder’s identity, and the wallet instance, so that trust can be verified across different infrastructures and trust frameworks? Or is this outside the semantics and part of the meta data in the attestation?</td>
<td><strong>Trust semantics:</strong> This is about semantic binding—how trust relationships are described and validated, not just cryptographically but meaningfully. It connects the modeling work to governance and policy semantics (who asserts what, on whose behalf, and under which trust framework).</td>
</tr>
</tbody>
</table>
