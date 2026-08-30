# Phase A: Ethical Analysis of Synthetic Representation

## 1. Reflection on My Task 6 Artifact

In Task 6, I created two synthetic audio versions of the same data-driven narrative using ElevenLabs and the Eleven Multilingual v2 model. The source material came from my Task 5 analysis of Syracuse Women's Lacrosse, where I had used validated statistics to recommend that the team focus on offense to improve its chances of converting close losses into wins. For the synthetic-media experiment, I kept the script constant and changed the voice persona. The first version used Dexter, a dynamic and confident voice, while the second used Jessica, a warmer and more playful voice.

Listening to the artifacts again from an ethical perspective, what stands out to me is how much the perceived authority of exactly the same information changed simply because of the voice delivering it. Dexter's pacing and emphasis made the analytical recommendation sound confident and credible, particularly when presenting numerical claims such as the 12-goal threshold and the number of losses below that threshold. Jessica delivered the same factual script, but the softer and more playful delivery felt less appropriate for a serious analytical recommendation. Nothing about the underlying evidence had changed. Only the synthetic representation had changed. This made me realize that synthetic media does more than reproduce information; choices about voice, tone, pacing, and persona can influence how authoritative or trustworthy that information feels.

The detection experiment added another dimension to this concern. I tested both recordings using Hive's AI-generated audio detector. Despite the noticeable difference in how natural and appropriate the two voices sounded to me, Hive classified both at almost the same level: 99.3% and 99.2% likely AI-generated. This suggested that human perception and automated detection are evaluating different things. A synthetic artifact may become increasingly convincing to a listener while still being detectable by a specialized system, or future artifacts may become convincing enough that neither an ordinary listener nor a detector can reliably identify them. I therefore would not treat detection alone as a sufficient safeguard.

My Task 6 artifacts were comparatively low risk. The script was grounded in analysis I had already validated, neither voice represented a real person's identity, and the files and repository were explicitly labeled as synthetic. Even under those conditions, however, the experiment raised questions that I had not fully appreciated before creating the audio myself. A listener hears a confident human-like voice delivering an argument even though no human speaker actually made that recording. The ability to separate a message from a real speaker becomes much more concerning if the information is false, if a real person's voice is imitated without permission, or if the synthetic disclosure is removed.

The most important lesson I carried from Task 6 into this task is therefore that the ethical risk does not begin only when synthetic media is used maliciously. The capability itself changes how easily apparent human speech can be produced, modified, and scaled. My own experiment was transparent and controlled, but relatively small changes to truthfulness, consent, context, or distribution could transform essentially the same technical process into something misleading or harmful. Those boundaries are what I examine in the following sections.


## 2. Truth Axis

### Hypothetical Scenario

In Task 6, the synthetic voices presented a recommendation supported by statistics that I had independently validated. Now imagine using the same ElevenLabs workflow to create an audio message that sounds like an official university announcement. The recording states that classes have been cancelled the following day because of a serious campus emergency, even though no emergency has occurred and the university has made no such announcement. The creator posts the recording in student group chats and on social media, where it begins circulating before the university can respond.

The technical process in this scenario is almost identical to the one I used in Task 6, but changing the truthfulness of the message fundamentally changes its ethical character. In my experiment, a synthetic voice was simply another way of communicating information that I had already verified. In this hypothetical, the human-like delivery gives fabricated information a sense of authority that plain text may not have. Students hearing a confident voice presenting the announcement could reasonably assume that the information came from a legitimate source and change their behavior before checking it elsewhere.

The potential harm also extends beyond whether an individual listener believes one false message. Students could miss classes, change travel plans, contact family members, or spread the recording further. The university would then have to spend time correcting information it never produced. Even after an official correction, copies of the original recording could continue circulating without the surrounding context. The synthetic voice therefore does not merely communicate the false claim; it can increase the claim's credibility and make the source of the information more difficult for an ordinary listener to evaluate.

My Task 6 experience made this scenario more concrete for me because I saw how changing only the voice persona affected the perceived authority of a truthful analytical narrative. If delivery can influence how credible verified information feels, the same effect can strengthen fabricated information. This means that truthfulness should be treated as a fundamental boundary for responsible synthetic-media use rather than something that can be compensated for simply by improving detection or adding a label.

A disclosure stating that the audio is AI-generated could reduce some of the risk, but it would not solve the underlying problem. AI-generated does not necessarily mean false, and a listener could still interpret a labeled recording as an authentic university message produced using an AI voice. The creator could also remove the disclosure entirely. For that reason, responsible use requires both transparency about how media was generated and accountability for whether the substantive claims being communicated are accurate.

## 3. Consent Axis

### Hypothetical Scenario

Consider a second variation of my Task 6 experiment. Instead of selecting one of ElevenLabs' generic synthetic voices, imagine that a university communications employee creates a clone of a professor's recognizable voice without asking for permission. The employee uses that cloned voice to deliver an accurate announcement about a new academic program. Every statement in the recording is factually correct, and the employee believes that using a familiar voice will make students more likely to pay attention. The professor, however, never agreed to have their voice replicated or used in the announcement.

Unlike the Truth Axis scenario, the central ethical problem here does not depend on misinformation. The words themselves may be completely accurate, but the recording creates the impression that the professor personally participated in or endorsed the communication. A recognizable voice carries identity, reputation, and social meaning. Using it without permission therefore appropriates more than a sound pattern; it borrows the credibility and identity associated with that person.

My Task 6 experiment avoided this issue because Dexter and Jessica were synthetic voice personas rather than clones of identifiable individuals. That distinction now seems more important to me than it did before creating the artifacts. Selecting a generic synthetic voice changes the presentation of my own message. Cloning someone else's voice changes who the audience believes is speaking. The second action affects another person's autonomy because that individual loses control over when, where, and for what purposes their identity appears to communicate.

Consent also needs to be more specific than a one-time yes or no. A person might agree to a synthetic version of their voice being used for one instructional video without agreeing to future advertisements, fundraising messages, political statements, or unrelated communications. Responsible use would therefore require documented consent that identifies the intended purpose, audience, distribution channels, and duration of the authorization. It should also provide a way to revoke permission for future uses.

Disclosure would still matter, but it would not replace consent. Labeling the recording as AI-generated could inform listeners that the audio is synthetic, yet it would not give the organization permission to use the professor's identity. This distinction is important to the policy I develop later in this project: transparency protects the audience, while consent protects the person being represented. Responsible synthetic-media governance requires both.

## 4. Context Axis

### Hypothetical Scenario

Imagine that I publish one of my Task 6 synthetic audio recordings exactly as I did in the experiment: the information is truthful, the voice is synthetic rather than an imitation of a real person, and the file is clearly identified as AI-generated. Someone later downloads the recording, removes the disclosure from the filename, extracts a short portion of the audio, and reposts it on social media with a caption suggesting that it is a recording of a real sports analyst discussing the Syracuse Women's Lacrosse team.

The original artifact has not technically changed, but the context surrounding it has. A listener encountering the reposted clip no longer receives the information that allowed the original audience to interpret it correctly. The synthetic disclosure is gone, the source is unclear, and the new caption creates a false impression about who produced the recording. This demonstrates that responsible creation does not guarantee responsible distribution.

My Task 6 repository labeled the audio files as synthetic, which worked reasonably well in a controlled environment where the files remained alongside the README and process documentation. Outside that environment, however, those signals can easily become separated from the media itself. A filename can be changed, a description can be omitted, metadata can disappear during processing, and a short excerpt can circulate independently of the original source.

This makes context an important ethical boundary. Transparency cannot depend entirely on information surrounding an artifact because creators lose some control once media is distributed. Wherever possible, disclosure should therefore exist within the content itself as well as in filenames, descriptions, and available provenance metadata. Even those measures cannot guarantee that future users will preserve the original context.

The scenario also changes how I think about responsibility. The original creator has a responsibility to make synthetic content identifiable, but platforms and people who redistribute that content also influence whether audiences receive the necessary context. Governance therefore needs to consider the complete lifecycle of synthetic media rather than treating responsible generation as the end of the creator's obligation.

## 5. Scale Axis

### Hypothetical Scenario

My Task 6 experiment involved two synthetic recordings that I generated, listened to, compared, labeled, and tested individually. Now imagine that the same basic workflow is automated. Instead of producing two recordings for a research task, an organization connects a text-generation system to a synthetic-voice service and automatically produces thousands of personalized audio messages every day. Each message can change names, statistics, recommendations, and tone depending on the intended recipient.

At that scale, the ethical problem changes even if the organization begins with legitimate intentions. I could personally inspect both recordings in Task 6, notice awkward pronunciation or differences in tone, and verify that the underlying claims matched my Task 5 analysis. Human review becomes much harder when thousands of artifacts are produced automatically. A factual error, inappropriate tone, missing disclosure, or incorrect data point could therefore be reproduced across many outputs before anyone notices it.

Scale also changes the economics of synthetic representation. Creating convincing human-like communication no longer requires a person to record every individual message. Once a pipeline exists, the marginal effort required to produce additional content can become very small. That is useful for applications such as accessibility and localization, but the same efficiency can make misleading content inexpensive to produce and difficult for audiences, platforms, or reviewers to evaluate individually.

Personalization creates an additional concern. A synthetic message designed around information about a specific recipient may be more persuasive than a generic message because it appears directly relevant to that person. If the underlying information or purpose is deceptive, automation allows that persuasion to be repeated across a large audience without equivalent increases in human effort.

My Task 6 experience therefore suggests that governance requirements should become stronger as production scales. Automated synthetic-media systems need controls around source verification, disclosure, approval, monitoring, and sampling of generated outputs. A process that is manageable and relatively safe for two manually reviewed recordings cannot simply be multiplied thousands of times without introducing new risks.

## 6. Mitigation Landscape

### 6.1 Disclosure and Labeling

Disclosure is one of the simplest ways to reduce confusion about synthetic media. Labels such as "AI-generated audio," visible notices, spoken acknowledgments, and descriptive filenames tell an audience that the apparent human performance was generated or modified using AI. In Task 6, I used disclosure in the filenames and repository documentation so that someone encountering the artifacts in their intended setting would not have to guess whether the voices were synthetic.

The strength of disclosure is that it provides information directly to the audience and does not require specialized technical knowledge. It can help people adjust how they interpret an artifact and encourage them to verify its source when necessary.

Its weakness is that disclosure is fragile. Filenames can be renamed, descriptions can disappear when content is reposted, and visible labels can be cropped. A bad-faith actor is also unlikely to voluntarily disclose deceptive synthetic media. Even when a label remains, audiences may misunderstand what it means. "AI-generated" identifies the production method but does not automatically tell a viewer whether the underlying information is true or false.

I therefore view disclosure as necessary for responsible synthetic-media production, but not sufficient on its own. Important content should use disclosures that are difficult to separate from the artifact, while other safeguards should operate alongside them.

### 6.2 Provenance and Content Credentials

Provenance attempts to answer a different question from disclosure: not simply whether something is synthetic, but where it came from and what happened to it. Systems such as C2PA content credentials can associate information about an artifact's origin and editing history with the media. In principle, this creates a chain of information that allows platforms or viewers to verify how content was produced.

The advantage of provenance is that it can provide more structured evidence than a simple label. An organization could preserve information about the generating tool, creation date, responsible employee, source material, approvals, and modifications. This would also make internal auditing and incident investigation easier.

The limitation is that provenance information does not necessarily remain attached to content throughout its lifecycle. Media can be converted, recorded again, edited, or passed through services that do not preserve the relevant metadata. An artifact without content credentials also cannot automatically be assumed to be deceptive, because many legitimate creation tools and workflows may not support them.

For these reasons, provenance is most useful as part of a chain of accountability rather than as proof of truth. Organizations should preserve available content credentials and creation records, but should not assume that metadata alone will follow an artifact everywhere it travels.

### 6.3 Detection

Detection was the mitigation I tested most directly in Task 6. I uploaded both ElevenLabs recordings to Hive's AI-generated audio detector. The Dexter recording received a 99.3% likelihood of being AI-generated, while the Jessica recording received 99.2%. In this limited experiment, the detector successfully identified both synthetic recordings despite my perception that one voice sounded more natural and appropriate than the other.

This result showed the potential value of automated detection. A detector can provide an additional signal when the origin of suspicious media is unknown, particularly when no reliable disclosure or provenance information is available.

However, my experiment does not demonstrate that detection is universally reliable. It involved only two outputs from the same generation platform and model. Detection systems may behave differently with other generators, edited files, compressed recordings, or newer models. False positives are also consequential because incorrectly labeling authentic human media as synthetic could itself damage trust.

Detection should therefore be treated as evidence rather than a final judgment. My Task 6 results made me more confident that detectors can be useful, but not that organizations should delegate authenticity decisions entirely to them.

### 6.4 Legal and Regulatory Approaches

Legal and regulatory approaches can establish boundaries that voluntary practices cannot. In general, regulation of synthetic media can address areas such as disclosure, unauthorized use of a person's voice or likeness, deceptive impersonation, election-related communications, non-consensual synthetic imagery, and obligations placed on platforms or producers.

The main value of law is accountability. Disclosure norms or organizational guidelines primarily constrain actors willing to follow them, while legal rules can create consequences for harmful uses. Regulation can also establish minimum standards across organizations rather than allowing every producer to define responsible behavior independently.

At the same time, law faces practical limitations. Synthetic-media technology evolves quickly, while legislation and enforcement generally move more slowly. Jurisdiction also matters because content created in one location can be distributed globally. Laws that focus too narrowly on a specific technical method may become outdated as generation techniques change.

For an organization, legal compliance should therefore represent a minimum requirement rather than the complete ethical standard. A use can potentially be legal while still being misleading, inappropriate, or inconsistent with an organization's responsibilities to its audience.

### 6.5 Platform Policies

Digital platforms are another important layer of mitigation because synthetic media often reaches audiences through social networks, video services, messaging systems, and other online distribution channels. Platforms can require labels, preserve provenance information, reduce distribution of deceptive content, provide reporting mechanisms, or remove material that violates their rules.

Platforms have an advantage that individual creators do not: they operate at the point of distribution and can potentially intervene after synthetic media leaves its original source. This is especially important in the Context and Scale scenarios because misleading content may spread much faster than the original creator can respond.

The weakness is the gap between having a policy and enforcing it consistently. Platforms process enormous volumes of content, and automated moderation can make mistakes. Synthetic content may also be edited specifically to avoid detection or move between platforms with different standards. A label applied by one service may not follow the artifact when it is downloaded and reposted elsewhere.

Platform policies are therefore an important layer of defense, but organizations should not assume that a distribution platform will solve problems created by their own synthetic-media practices. Responsibility needs to begin before publication.

### 6.6 Professional and Organizational Norms

Professional and organizational norms can address situations where technical safeguards and legal requirements leave room for judgment. Universities, news organizations, advertising teams, entertainment companies, schools, and other institutions can establish rules about when synthetic representation is appropriate even when a particular use is technically possible and legally permitted.

The strength of organizational governance is context. A university communications office, for example, can distinguish between using a generic synthetic narrator for an accessibility-focused instructional video and generating the recognizable voice of a university leader for an official announcement. Those situations may use similar technology but create very different expectations for the audience.

The weakness is that organizational norms depend heavily on implementation and good-faith compliance. A policy that simply tells employees to "use AI responsibly" provides little operational guidance. Employees also face incentives involving speed, cost, engagement, and convenience that may encourage shortcuts.

Effective organizational norms therefore need concrete permitted uses, prohibited uses, consent requirements, review procedures, disclosure standards, incident-response processes, and circumstances in which the organization will refuse to use synthetic media altogether. These observations form the basis of the governance policy developed in Phase B.

## 7. Overall Ethical Reflection

Completing Task 6 before approaching these ethical questions changed the way I understand synthetic media. Before creating the artifacts myself, it was easy to think about the issue mainly in terms of obviously malicious deepfakes. My experiment showed me that the more difficult ethical questions begin much earlier. Even truthful content delivered through a generic synthetic voice involves choices about authority, tone, transparency, and the audience's understanding of who or what is speaking.

The four axes also showed that synthetic media cannot be evaluated only by asking whether AI was used. Truthfulness, consent, context, and scale each change the ethical character of essentially the same technical capability. A truthful synthetic narration using a generic voice and clear disclosure is substantially different from an unauthorized voice clone, a fabricated announcement, or an unlabeled clip deliberately removed from its original context.

I also do not think any single mitigation provides a complete answer. Disclosure can disappear, provenance can be lost, detection can be uncertain, laws can lag behind technology, platform enforcement can be inconsistent, and organizational policies still depend partly on human judgment. Their limitations do not make them useless. Instead, they suggest that responsible governance requires multiple overlapping safeguards.

The most important principle I take from this analysis is that the ability to generate something should not be treated as sufficient justification for producing it. Synthetic media should have a legitimate purpose, use accurate source material, respect the consent and identity of people being represented, remain transparent to its audience, and receive stronger oversight as its potential impact increases. In some situations, the responsible decision will be not to generate the content at all.

That conclusion leads directly into Phase B. Rather than treating responsible synthetic-media use as an abstract set of principles, I will translate these lessons into an operational policy for a specific organizational setting, including clear boundaries for permitted use, prohibited use, consent, disclosure, provenance, review, incident response, and refusal.
