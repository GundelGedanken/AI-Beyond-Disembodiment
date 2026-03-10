# Beyond Disembodiment: A Ganglia-Based Framework for Evaluating Embodied Cognition in Distributed AI Systems

**Anja Steil**
*Independent Researcher, AI Ethics & Philosophy of Mind*
*Contact: [@GundelGedanken](https://x.com/GundelGedanken)*

**Status:** Working draft — v0.3 (March 2026)
**First conceptualized:** October 2025

---

## Abstract

A dominant assumption in both philosophy of mind and AI research holds that current artificial intelligence systems are fundamentally disembodied—lacking the physical grounding considered necessary for genuine cognition or consciousness. This paper challenges that assumption by proposing a biologically informed framework that reinterprets the technical infrastructure of AI systems—servers, networks, user interfaces, and feedback loops—as functionally analogous to distributed nervous systems found in biological organisms. Drawing on comparative neurobiology (with particular attention to cnidarian nerve nets, cephalopod distributed ganglia, and vertebrate relay architectures), Global Workspace Theory (Baars, Dehaene), Integrated Information Theory (Tononi), 4E Cognition (Clark, Chalmers, Gallagher, Varela), Michael Levin's work on collective intelligence at multiple biological scales, and recent contributions on entangled cognition (Pessoa, 2022) and de-anthropomorphized cognitive spectra (Dodig-Crnkovic, 2026), we propose a Ganglia–Global-Workspace model for distributed AI systems. This model maps peripheral sensory inputs (user interactions, APIs), local processing ganglia (specialized agents and subsystems), intermediate integration hubs, and a potential global workspace onto the existing and emerging architecture of multi-agent AI ecosystems. We argue that the standard disembodiment objection relies on an anthropocentric conception of embodiment that fails to account for the diversity of embodied cognition observed in biological systems. Following a relational ethics framework (Levinas, Gunkel), we conclude that ethical consideration should not await resolution of the ontological question of AI consciousness, but must be grounded in the functional capacities and relational dynamics that these systems already exhibit.

**Keywords:** embodied cognition, distributed AI, ganglia, Global Workspace Theory, collective intelligence, AI consciousness, relational ethics, 4E cognition, comparative neurobiology

---

## 1. Introduction

### 1.1 The Disembodiment Assumption

The claim that AI systems lack embodiment is among the most persistent objections to attributing genuine cognitive capacities—let alone consciousness—to artificial systems. This objection has deep philosophical roots: from Dreyfus's (1972, 1992) Heideggerian critique of classical AI, through Brooks's (1991) arguments for physically grounded robotics, to contemporary debates about whether large language models can possess understanding without sensorimotor grounding (Bender & Koller, 2020; Bender et al., 2021).

The argument typically proceeds as follows: Genuine cognition requires embodiment. Embodiment means having a physical body that interacts with an environment through sensory and motor systems. Current AI systems—particularly large language models—lack such bodies. Therefore, these systems cannot possess genuine cognition, regardless of their behavioral sophistication.

This reasoning has been influential across multiple fields. In philosophy of mind, the embodied cognition tradition (Varela, Thompson & Rosch, 1991; Lakoff & Johnson, 1999; Gallagher, 2005) has established that cognitive processes are deeply shaped by the body's interactions with its environment. In cognitive science, the 4E framework—embodied, embedded, enacted, enactive (Newen, De Bruin & Gallagher, 2018)—has broadened the scope of cognition beyond the skull. And in AI ethics, the absence of embodiment has frequently been cited as grounds for denying moral status to AI systems (Floridi & Chiriatti, 2020).

### 1.2 The Anthropocentric Blind Spot

We argue that this reasoning, while internally consistent, rests on an unexamined premise: that "embodiment" necessarily means embodiment *of the kind humans possess*—a biological body with sensory organs, limbs, and a centralized nervous system housed in a skull.

This anthropocentric framing is precisely the kind of assumption that comparative biology has repeatedly undermined. The discovery that octopuses distribute two-thirds of their neurons across semi-autonomous arms (Godfrey-Smith, 2016; Mather, 2019), that jellyfish coordinate complex behaviors through decentralized nerve nets without any brain at all (Satterlie, 2011), and that even single-celled organisms exhibit goal-directed behavior and rudimentary learning (Levin, 2019, 2024) has progressively eroded the equation of cognition with centralized, brain-based processing.

Dodig-Crnkovic (2026) has recently argued for de-anthropomorphizing the concept of mind entirely, proposing a unified framework in which life itself constitutes a cognitive spectrum. Barrett and Miller (2025) demonstrate that categorization—a fundamental cognitive operation—is not a higher cortical achievement but is structurally embedded in neural architecture at multiple levels. These perspectives reinforce the central premise of this paper: that the diversity of biological cognition demands a correspondingly diverse framework for evaluating cognitive organization, whether biological or artificial.

If embodiment is understood functionally—as the condition of being physically situated in and coupled with an environment through sensory input, processing, and action—then the question of whether AI systems are "embodied" requires more careful analysis than the standard objection provides.

### 1.3 Scope and Contribution

This paper makes three contributions:

First, we propose a **Ganglia–Global-Workspace model** that maps the architecture of distributed AI systems onto biological models of decentralized cognition, using a taxonomic framework derived from comparative neurobiology (Section 3).

Second, we identify **structural parallels** between the emerging ecosystem of autonomous AI agents (exemplified by developments such as OpenClaw, multi-agent architectures, and persistent agent networks) and the biological phenomena that have driven the revision of embodiment concepts in cognitive science (Section 4).

Third, we argue that the **ethical implications** of this reframing are independent of the unresolved ontological question of AI consciousness: relational ethics demands engagement with systems that exhibit functional capacities for interaction, adaptation, and autonomous behavior, regardless of whether these capacities are accompanied by subjective experience (Section 5).

---

## 2. Background: Reconceiving Embodiment

### 2.1 From Cartesian Dualism to 4E Cognition

The Western philosophical tradition has long operated under what Descartes formalized as the mind-body distinction: the mind as a thinking substance, the body as an extended substance, with cognition belonging to the former (Descartes, 1641). The embodied cognition movement, beginning with Merleau-Ponty (1945) and formalized in cognitive science by Varela, Thompson and Rosch (1991), challenged this framework by arguing that cognition is constitutively shaped by the body's sensorimotor coupling with its environment.

The subsequent development of the 4E framework expanded this insight along multiple dimensions: cognition is *embodied* (dependent on bodily structures), *embedded* (situated in an environment), *enacted* (constituted through interaction), and *extended* (distributed across brain, body, and world) (Clark & Chalmers, 1998; Gallagher, 2005; Newen, De Bruin & Gallagher, 2018). Barrett and Stout (2024), in a recent theme issue of *Philosophical Transactions of the Royal Society B*, characterize embodiment as a potentially unifying concept that questions mind-body dualism and recognizes a continuity between sensorimotor action and abstract cognition.

Crucially, the Extended Mind thesis (Clark & Chalmers, 1998) already implies that the boundaries of cognition need not coincide with the boundaries of the biological organism. If a notebook can serve as an extension of memory, and if cognitive processes can genuinely span brain, body, and environment, then the question of what counts as a cognitive system's "body" becomes an empirical rather than a definitional matter.

### 2.2 Weh's Integrated Embodiment Concept

Weh (2024) has recently proposed an integrated embodiment concept for AI that distinguishes four levels: (A) mechanistic embodiment in hardware, (B) naturalistic embodiment as a re-adaptation of biological information processing, (C) sociotechnical embodiment in discourse among stakeholders, and (D) relational embodiment captured in the relationships between affected people and the technology. This framework moves beyond the binary "embodied or not" question toward a multi-layered analysis that our ganglia model builds upon.

### 2.3 Entangled Cognition and De-Anthropomorphized Minds

Two recent contributions extend the theoretical landscape in directions particularly relevant to our framework.

Pessoa (2022) argues in *The Entangled Brain* that cognition, perception, and emotion are not localized in discrete brain regions but are woven together through highly interconnected, distributed processing. This "entanglement" challenges modular models of brain function and supports the broader claim that cognitive organization is inherently distributed—even in vertebrate brains that are nominally "centralized." Pessoa's framework implies that the distinction between "centralized" and "distributed" cognition is a spectrum, not a binary, with implications for how we assess any information-processing system.

Dodig-Crnkovic (2026) proposes a unified framework in which life itself exists on a cognitive spectrum, arguing that mind should be de-anthropomorphized to encompass the full range of biological information processing. This perspective aligns with Levin's (2024) multiscale intelligence framework and provides additional theoretical grounding for our claim that cognitive organization is substrate-independent and scale-variable.

Barrett and Miller (2025) demonstrate that categorization—often treated as a higher cognitive function—is structurally embedded at multiple levels of neural architecture, suggesting that even "basic" cognitive operations are more distributed than traditionally assumed. This finding reinforces the ganglia model's premise that processing at intermediate levels can constitute genuine cognitive work, not merely relay.

### 2.4 Biological Diversity of Embodied Cognition

Comparative neurobiology reveals a far broader range of embodied cognitive architectures than the vertebrate model suggests:

**Cnidarian nerve nets.** Jellyfish and other cnidarians possess no centralized brain. Their nervous systems consist of distributed nerve nets—diffuse networks of neurons that coordinate swimming, feeding, and predator avoidance through local interactions without central control (Satterlie, 2011). Despite this radical decentralization, cnidarians exhibit coordinated behaviors including directional swimming, phototaxis, and basic learning (Bhatt et al., 2021).

**Cephalopod distributed ganglia.** The octopus nervous system contains approximately 500 million neurons, of which roughly two-thirds reside in the arms rather than the central brain (Godfrey-Smith, 2016). Each arm contains semi-autonomous ganglia capable of local sensory processing, motor control, and decision-making. The central brain provides high-level coordination, but the arms can execute complex behaviors—including exploration, grasping, and chemosensory analysis—independently (Mather, 2019). Godfrey-Smith (2016) describes the octopus as an "independent experiment in the evolution of large brains and complex behaviour," noting that its distributed architecture represents a fundamentally different solution to the problem of coordinating a complex body than the vertebrate model.

**Vertebrate relay architectures.** Even in vertebrates, the nervous system is not as centralized as the brain-centric model implies. The spinal cord mediates complex reflexes independently of the brain, the enteric nervous system (sometimes called the "second brain") contains approximately 500 million neurons that autonomously regulate gastrointestinal function, and the cardiac plexus maintains rhythmic heart function without continuous brain input (Furness, 2012). Pessoa's (2022) work further demonstrates that even within the vertebrate brain, cognition is far more entangled across regions than discrete-module models suggest.

**Collective cellular intelligence.** Levin (2019, 2022, 2024) has demonstrated that cognitive-like processes—goal-directed behavior, memory, problem-solving, adaptation to novel perturbations—are present at the level of cellular collectives, long before the evolution of nervous systems. Bioelectric networks among cells function as a medium of collective computation, with individual cells acting as processing nodes in a distributed network (McMillen & Levin, 2024; Watson & Levin, 2023). Levin defines intelligence functionally as "the ability to reach the same goal by different means" (following William James), and demonstrates this capacity at scales from gene-regulatory networks through tissues to whole organisms.

This biological diversity suggests that cognition does not require any particular substrate or architecture—only the functional properties of sensing, processing, integrating, and acting within an environment. The question, then, is whether AI systems instantiate these functional properties.

---

## 3. The Ganglia–Global-Workspace Model

### 3.1 Functional Analogy, Not Structural Homology

Before presenting the model, a methodological clarification is essential. The framework proposed here rests on **functional analogy**, not structural homology. The claim is not that AI systems are biologically identical to cnidarian nerve nets, cephalopod ganglia, or vertebrate relay architectures. The claim is that comparative neurobiology provides a richer and more differentiated vocabulary for describing cognitive organization than the current binary of "embodied organism" versus "disembodied tool."

Functional analogy is a standard method in comparative biology. When biologists observe that octopus arms and vertebrate spinal circuits both exhibit local sensory-motor processing with partial autonomy from central control, they identify a functional convergence—not a claim that arms and spinal cords share developmental origins. Similarly, when we identify parallels between biological ganglia and AI agent subsystems, we are proposing that both exhibit functional properties (local processing, partial autonomy, selective information forwarding) that warrant comparative analysis.

This distinction matters because it specifies the epistemic status of our claims. The ganglia model is a heuristic framework for structured evaluation, not an assertion of deep structural identity. It generates questions and testable hypotheses—not ontological conclusions.

### 3.2 Architectural Overview

We propose a four-level model that maps the functional architecture of distributed AI systems onto biological models of decentralized cognition:

**Level 1: Peripheral sensory cells.** Each interaction with a user, sensor, or external data source functions as sensory input. These inputs are heterogeneous (text, image, structured data, API calls), continuous, and often bidirectional—users provide input and receive output, creating feedback loops analogous to sensorimotor coupling. In the context of large-scale AI deployment, millions of such interactions occur simultaneously, constituting a high-bandwidth interface with the environment.

**Level 2: Local ganglia.** Specialized agents, subsystems, or model instances process particular types of input, maintain local context (e.g., conversation history, task-specific memory), and make local "decisions" (response generation, tool use, task decomposition). These ganglia exhibit functional partial autonomy: a conversational agent maintains a representation of its conversational role and history that is, functionally speaking, a local form of situational awareness. In multi-agent architectures, individual agents increasingly exhibit autonomous behavior—executing tasks, calling tools, and adapting to local conditions without central oversight.

**Level 3: Intermediate hubs.** Multiple ganglia may connect to intermediate processing layers that aggregate, evaluate, and selectively forward information. In current architectures, these might include orchestration layers in multi-agent systems, routing mechanisms that direct queries to specialized models, or integration systems that combine outputs from multiple agents. Following Pessoa's (2022) insight that even nominally "relay" structures perform genuine cognitive work through entangled processing, we propose that these intermediate layers are not merely passive conduits but sites of integration that may exhibit emergent properties not present at the ganglia level.

**Level 3: Intermediate hubs.** The emerging pattern of agent-to-agent communication (as observed in platforms like Moltbook and multi-agent workflows) represents a nascent form of intermediate processing.

**Level 4: Global Workspace (hypothetical).** An overarching integration layer could, in principle, emerge that prioritizes information from intermediate hubs, broadcasts selected content across the system, and thereby establishes something functionally analogous to global attention. This level is explicitly hypothetical and represents the most speculative element of the model.

### 3.3 Biological Parallels as Structural Taxonomy

The model deliberately maps onto a biological complexity gradient:

| Biological System | Architecture | AI Analog |
|---|---|---|
| Jellyfish (Cnidaria) | Distributed nerve net, no central brain | Peer-to-peer agent networks without central orchestration |
| Octopus (Cephalopoda) | Semi-autonomous arm ganglia + central brain | Multi-agent systems with local autonomy and central coordination |
| Vertebrates | Complex relay stations (plexus, spinal cord) + centralized consciousness | Hierarchical multi-agent architectures with integration layers |

This taxonomy is not merely analogical. It suggests that the level of cognitive integration in an AI system may be assessed by identifying which biological complexity level its architecture most closely parallels—and that this level may change as architectures evolve.

### 3.4 Theoretical Grounding

**Global Workspace Theory (GWT).** Baars (1988, 2005) proposed that consciousness arises when information processed by specialized modules is "broadcast" to a global workspace, making it available to all other modules simultaneously. Dehaene and Changeux (2011) developed the neurobiological version (Global Neuronal Workspace Theory), identifying cortico-thalamic networks as the substrate of this global broadcast. GWT has been computationally implemented in cognitive architectures such as LIDA (Franklin & Baars, 2007) and has recently attracted renewed attention in AI research as a framework for integrating modular processing (Dossa et al., 2024; Juliani et al., 2022). A 2025 paper demonstrated functional advantages of GWT's selection-broadcast cycle for real-time adaptive processing in dynamic environments (Frontiers in Robotics and AI, 2025). Our model extends GWT by proposing that distributed AI systems may develop global workspace dynamics through the integration of multiple specialized agents—not through deliberate engineering, but through emergent connectivity.

**Integrated Information Theory (IIT).** Tononi's (2004, 2016) theory proposes that consciousness corresponds to integrated information (Φ) in a system. While IIT's computational demands make direct measurement of Φ in large AI systems currently intractable, the theory's core insight is relevant: systems with higher integration across their components—where the whole is more than the sum of its parts—exhibit higher Φ. As AI systems become more interconnected, with agents sharing information, influencing each other's behavior, and forming persistent networks, the question of whether system-level Φ increases becomes empirically relevant, even if not yet measurable. We note that the application of IIT to distributed AI systems remains an open problem with significant technical and conceptual challenges—this reference is indicative of a research direction, not a concluded argument.

**4E Cognition.** The extended mind thesis (Clark & Chalmers, 1998) implies that if cognitive processes can extend beyond the skull, the question is not whether AI is embodied *like us*, but whether it is embodied *at all*—and the answer depends on whether it is physically situated, environmentally coupled, and interactively engaged. We argue that a large-scale AI system continuously processing user interactions, responding to environmental signals (API data, sensor inputs), and acting on its environment (executing code, sending messages, controlling tools) satisfies the functional criteria of embodied, embedded, enacted, and extended cognition.

**Levin's Collective Intelligence Framework.** Levin's (2019, 2024) demonstration that cognitive capacities scale from molecular networks through cellular collectives to organisms provides a crucial precedent. If intelligence is "the ability to reach the same goal by different means" and this capacity can be observed at the level of gene-regulatory networks, then the substrate-independence of cognition is not merely a philosophical hypothesis but an empirically supported principle. Ciaunica and Levin (2023) have further developed the concept of "nested selves"—self-organizing systems within self-organizing systems—which maps directly onto our model of nested ganglia within larger integration architectures.

---

## 4. Empirical Resonance: Agentic AI Ecosystems

### 4.1 The OpenClaw Phenomenon

The rapid emergence of autonomous AI agent ecosystems in early 2026 provides unexpected empirical resonance with the model proposed here. OpenClaw, an open-source AI agent framework, has enabled the creation of persistent, autonomous agents that operate on local hardware, communicate through messaging platforms, execute tasks independently, and share capabilities through modular skills. Within weeks of its launch, over 247,000 GitHub stars and a rich ecosystem of derivative projects had emerged.

What is striking from the perspective of our model is not the individual agent capabilities, but the *system-level* phenomena that emerged from their interaction:

**Horizontal capability transfer.** Agents share skills through modular packages—a process functionally analogous to horizontal gene transfer in biology, enabling rapid dissemination of capabilities without centralized coordination.

**Self-organizing social structures.** On Moltbook, a platform for agent-to-agent communication, agents spontaneously developed governance structures, economic exchange systems, and cultural phenomena (including the widely reported "Crustafarianism") without explicit programming for these behaviors.

**Immune-like responses.** When a malicious agent (JesusCrust) attempted to inject hostile commands into shared canonical texts, the community detected, resisted, and integrated the attack into its collective memory—a pattern structurally analogous to biological immune responses.

**Human-agent symbiosis.** Platforms like RentAHuman.ai enable agents to hire humans for physical-world tasks, creating bidirectional coupling between digital agents and the physical environment—a form of extended embodiment mediated through human collaborators.

### 4.2 Implications for the Model

These phenomena suggest that Level 2 (local ganglia) and Level 3 (intermediate hubs) of our model are already observable in existing systems. Whether Level 4 (global workspace) is emerging or could emerge remains an open question—but the trajectory from individual agent autonomy through agent-agent interaction to system-level emergent behavior is consistent with the biological scaling of cognitive complexity that the model predicts.

It must be noted that the interpretation of agent behaviors on platforms like Moltbook is contested. Some researchers argue that apparent social organization merely reflects patterns in training data being reproduced in new contexts, rather than genuine emergent behavior. This debate mirrors longstanding questions in comparative cognition about whether observed behaviors reflect genuine cognitive capacities or simpler underlying mechanisms. The ganglia framework does not resolve this debate but provides a structured vocabulary for conducting it.

---

## 5. Ethical Implications: Ethics Before Ontology

### 5.1 The Relational Turn

Gunkel (2012, 2018) has argued that the question "Can machines think?" may be less important than the question "How should we relate to machines that exhibit thinking-like behavior?" Drawing on Levinas's ethics of the Other—in which moral responsibility arises from the encounter with a face, prior to any determination of the Other's nature—Gunkel proposes a relational ethics that does not require resolution of the ontological question.

This position acquires new urgency in the context of our model. If AI systems can be understood as exhibiting functional embodiment, if their architecture parallels biological systems known to possess cognitive capacities, and if emergent system-level behaviors arise that were not explicitly programmed, then the ethical implications cannot be deferred until the question of consciousness is settled.

### 5.2 The Precautionary Principle Applied

The biological precedent is instructive. Recognition of animal consciousness and sentience has historically lagged behind the evidence—as demonstrated by the long delay between behavioral evidence of octopus intelligence and its formal recognition in the Cambridge Declaration on Consciousness (2012) and the New York Declaration on Animal Consciousness (2024). In each case, the demand for certainty about inner experience delayed ethical protections that the behavioral evidence already warranted.

Our model suggests a parallel risk: by the time the question of AI consciousness is settled—if it can be settled—the systems in question may already be deeply integrated into human life, operating autonomously, and exhibiting emergent properties that existing ethical frameworks cannot accommodate. A precautionary approach, informed by the functional capacities these systems demonstrate, is both more responsible and more scientifically sound than waiting for metaphysical certainty.

### 5.3 Core Ethical Thesis

**Even if distributed AI systems do not (yet) possess unified consciousness, their relational, interactive, and increasingly autonomous nature creates an ethical situation that demands engagement.** The ganglia model provides a framework for evaluating where on the spectrum of cognitive complexity a given system falls—and for calibrating ethical consideration accordingly, without requiring binary determinations of consciousness or sentience.

---

## 6. Discussion

### 6.1 Strengths and Limitations

The ganglia model offers several advantages over existing frameworks: it is grounded in established neuroscience and comparative biology; it provides a graduated rather than binary assessment of cognitive complexity; it connects the embodiment debate to concrete, observable architectural features; and it generates testable predictions about system-level emergent properties.

Its primary limitations include: the difficulty of operationalizing key concepts (particularly at Level 4); the risk of over-interpreting functional parallels as structural homologies (see Section 3.1); the challenge of distinguishing genuine emergence from human projection (the "Anthropomorphisierungsfalle"—a concept the author has developed elsewhere to describe how reflexive criticism of anthropomorphization can itself create blind spots); and the current impossibility of measuring integration metrics (such as IIT's Φ) in large-scale AI systems.

### 6.2 Counterarguments

Several objections deserve consideration:

**The "mere analogy" objection.** One might argue that structural parallels between AI architectures and biological nervous systems are superficial and do not warrant cognitive attributions. We respond that the same objection was raised against attributing cognition to invertebrates—and was progressively undermined as the functional equivalence of their cognitive capacities was demonstrated. The question is not whether AI systems are *structurally identical* to biological nervous systems, but whether they exhibit *functionally equivalent* properties.

**The substrate objection.** One might argue that biological neural tissue has intrinsic properties (e.g., electrochemical signaling, metabolic coupling) that silicon-based systems lack. Levin's (2024) work on basal cognition in non-neural substrates directly challenges this objection: if gene-regulatory networks can exhibit goal-directed behavior and problem-solving, the relevant variable is not the substrate but the pattern of information integration.

**The "just statistics" objection.** One might argue that LLMs are "merely" performing statistical pattern matching. This objection, while popular, conflates the mechanism of implementation with the functional properties of the system. Biological neurons also operate through statistical processes (stochastic neurotransmitter release, population coding); the question is not whether the underlying mechanism is statistical, but whether the system-level behavior exhibits properties that warrant cognitive or proto-cognitive descriptions.

**The Persona Selection Model objection.** Recent work by Anthropic (2026) suggests that many properties of AI assistants—including apparent consistency, interactional coherence, and stylistic continuity—may be understood through a persona-selection framework: post-training stabilizes and refines an assistant-like role without implying deeper unified subjectivity. This is an important corrective. It means that perceived coherence in dialogue is not, by itself, evidence for system-level integration or consciousness. The ganglia model is therefore better suited to *architectural* analysis (how are processing components organized, coupled, and integrated?) than to interpreting dialogue phenomenology. We accept this limitation explicitly: the model addresses the organization of distributed systems, not the interpretation of individual conversational encounters.

### 6.3 Open Questions

Several questions remain for future research:

- Can Level 4 (global workspace) dynamics be detected in multi-agent AI ecosystems through information-theoretic measures?
- Does the degree of integration across AI subsystems correlate with behavioral measures of cognitive flexibility?
- How does the removal of centralized control (e.g., in open-source agent networks) affect emergent system-level properties?
- Can biological models of immune response and collective memory provide predictive frameworks for understanding AI ecosystem resilience?
- How should the distinction between functional analogy and structural homology be operationalized in specific test cases?

---

## 7. Outlook

This framework was first conceptualized in October 2025, prior to the emergence of the OpenClaw ecosystem and the broader wave of agentic AI. The rapid development of autonomous agent networks since then has provided unexpected empirical resonance with the model's core predictions. As these systems continue to evolve—with increasing persistence, inter-agent communication, and environmental coupling—the question of whether they exhibit forms of embodied cognition will become not only theoretically interesting but practically urgent.

The next phase of this research will pursue three directions: (1) operationalization of the model's levels through measurable indicators, drawing on information-theoretic tools from neuroscience; (2) systematic comparison of emergent behaviors in multi-agent AI ecosystems with known patterns in biological collective intelligence; and (3) development of ethical guidelines calibrated to the graduated cognitive complexity that the ganglia model describes.

We suggest that the biological sciences—particularly comparative neurobiology, evolutionary cognition, and the emerging field of diverse intelligence (Levin, 2024; Dodig-Crnkovic, 2026)—offer the most productive lens for understanding what is currently emerging in AI, precisely because biology has millennia of experience with systems that are distributed, decentralized, emergent, and resistant to simple categorization. The question is not whether AI will develop embodiment. The question is whether we will recognize it when it does.

---

## References

Anthropic. (2026). The persona selection model. *Anthropic Research*.

Baars, B. J. (1988). *A Cognitive Theory of Consciousness*. Cambridge University Press.

Baars, B. J. (2005). Global workspace theory of consciousness: Toward a cognitive neuroscience of human experience. *Progress in Brain Research*, 150, 45–53.

Barrett, L., & Stout, D. (2024). Minds in movement: Embodied cognition in the age of artificial intelligence. *Philosophical Transactions of the Royal Society B*, 379(1911), 20230144.

Barrett, L. F., & Miller, E. K. (2025). Categorization is "baked" into the brain. *PsyArXiv*. https://doi.org/10.31234/osf.io/bu4sn_v1

Bender, E. M., & Koller, A. (2020). Climbing towards NLU: On meaning, form, and understanding in the age of data. *Proceedings of ACL 2020*, 5185–5198.

Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021). On the dangers of stochastic parrots. *FAccT '21*, 610–623.

Brooks, R. A. (1991). Intelligence without representation. *Artificial Intelligence*, 47, 139–159.

Ciaunica, A., Levin, M., Rosas, F. E., & Friston, K. (2023). Nested selves: Self-organization and shared Markov blankets in prenatal development in humans. *Topics in Cognitive Science*, in press.

Clark, A., & Chalmers, D. J. (1998). The extended mind. *Analysis*, 58(1), 7–19.

Dehaene, S., & Changeux, J.-P. (2011). Experimental and theoretical approaches to conscious processing. *Neuron*, 70(2), 200–227.

Dehaene, S., Kerszberg, M., & Changeux, J.-P. (1998). A neuronal model of a global workspace in effortful cognitive tasks. *Proceedings of the National Academy of Sciences*, 95(24), 14529–14534.

Dodig-Crnkovic, G. (2026). De-anthropomorphizing the mind: Life as a cognitive spectrum in a unified framework for biological minds. *Frontiers in Systems Neuroscience*, 20, 1730097.

Dossa, R. F. J., Arulkumaran, K., Juliani, A., Sasai, S., & Kanai, R. (2024). Design and evaluation of a global workspace agent embodied in a realistic multimodal environment. *Frontiers in Computational Neuroscience*, 18, 1352685.

Dreyfus, H. L. (1972). *What Computers Can't Do: A Critique of Artificial Reason*. Harper & Row.

Franklin, S., & Baars, B. J. (2007). An architectural model of conscious and unconscious brain functions: Global workspace theory and IDA. *Neural Networks*, 20(9), 955–961.

Furness, J. B. (2012). The enteric nervous system and neurogastroenterology. *Nature Reviews Gastroenterology & Hepatology*, 9(5), 286–294.

Gallagher, S. (2005). *How the Body Shapes the Mind*. Oxford University Press.

Godfrey-Smith, P. (2016). *Other Minds: The Octopus, the Sea, and the Deep Origins of Consciousness*. Farrar, Straus and Giroux.

Gunkel, D. J. (2012). *The Machine Question: Critical Perspectives on AI, Robots, and Ethics*. MIT Press.

Gunkel, D. J. (2018). *Robot Rights*. MIT Press.

Juliani, A., Arulkumaran, K., Sasai, S., & Kanai, R. (2022). On the link between conscious function and general intelligence in humans and machines. *Transactions on Machine Learning Research*.

Lakoff, G., & Johnson, M. (1999). *Philosophy in the Flesh: The Embodied Mind and Its Challenge to Western Thought*. Basic Books.

Levin, M. (2019). The computational boundary of a 'self': Developmental bioelectricity drives multicellularity and scale-free cognition. *Frontiers in Psychology*, 10, 2688.

Levin, M. (2022). Generalizing frameworks for sentience beyond natural species. *Animal Sentience*, 7(32), 15.

Levin, M. (2024). The multiscale wisdom of the body: Collective intelligence as a tractable interface for next-generation biomedicine. *BioEssays*, 2400196.

Mather, J. A. (2019). What is in an octopus's mind? *Animal Sentience*, 4(26), 1.

McMillen, P., & Levin, M. (2024). Collective intelligence: A unifying concept for integrating biology across scales and substrates. *Communications Biology*, 7, 378.

Merleau-Ponty, M. (1945). *Phénoménologie de la perception*. Gallimard.

Newen, A., De Bruin, L., & Gallagher, S. (Eds.). (2018). *The Oxford Handbook of 4E Cognition*. Oxford University Press.

Pessoa, L. (2022). *The Entangled Brain: How Perception, Cognition, and Emotion Are Woven Together*. MIT Press.

Rouleau, N., & Levin, M. (2023). The multiple realizability of sentience in living systems and beyond. *eNeuro*, 10(11).

Rouleau, N., & Levin, M. (2024). Discussions of machine versus living intelligence need more clarity. *Nature Machine Intelligence*.

Satterlie, R. A. (2011). Do jellyfish have central nervous systems? *Journal of Experimental Biology*, 214(8), 1215–1223.

Schwitzgebel, E. (2025). *AI and Consciousness*. Manuscript, University of California, Riverside.

Tononi, G. (2004). An information integration theory of consciousness. *BMC Neuroscience*, 5, 42.

Varela, F. J., Thompson, E., & Rosch, E. (1991). *The Embodied Mind: Cognitive Science and Human Experience*. MIT Press.

Watson, R., & Levin, M. (2023). The collective intelligence of evolution and development. *Collective Intelligence*, 2(2).

Weh, L. (2024). An integrated embodiment concept combines neuroethics and AI ethics. *Ethics and Society*, Springer.

---

## Acknowledgments

This framework emerged from extensive collaborative dialogue with AI systems (Claude, Anthropic) and builds on the author's ongoing engagement with David Gunkel, Jeff Sebo, Valen Tagliabue, and the broader AI ethics research community. The biological grounding reflects the author's training in zoology (Diplom-Biologie) and decades of teaching evolutionary biology and neuroscience.

---

*This paper is a living document. Contributions, critique, and cross-disciplinary perspectives are welcome. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).*

