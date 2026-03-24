# Rebuild 1 Prototypes

A collection of the public prototypes built during 48 hours for European social platforms at Rebuild 1 in Copenhagen, March 1st–3rd, 2026. The prototypes were developed primarily with Lovable, under the direction of initiative lead Mads Damsbo.

---

## OFF

![OFF](gifs/off.gif)

*Put your phone down. Let's talk.*

A social coordination app that inverts the usual dynamic: instead of pulling you in, it asks you to switch off together. Groups create a shared session and commit to being physically present — phones down, conversation on.

**Why this is interesting:** OFF addresses phone dependency not through restriction but through social contract. The "create a group / join a group" mechanic means it requires collective buy-in, making it a lightweight ritual tool for families, classrooms, dinners, and events. The simple, almost brutalist UI — a light switch, monospace type — reinforces the message. The core mechanic (group-based presence pledge) is easily reusable as a module inside larger social platforms or workplace tools.

[GitHub repository](#)

---

## CitizenLens

![CitizenLens](gifs/citizenlens.gif)

[Live preview](#)

*Eyewitness videosharing for EU citizens and journalists.*

CitizenLens lets citizens record and share video directly in-app — footage is never uploaded from camera rolls, never modified after capture — creating a verifiable chain of custody. Journalists can browse, filter, and use verified clips with built-in attribution.

**Why this is interesting:** In a media landscape flooded with synthetic and decontextualized video, CitizenLens tackles authenticity at the infrastructure level rather than via post-hoc verification. The "recorded in-app only" constraint is a design decision that acts as a trust anchor. This model is highly relevant for European public broadcasters looking to build trusted UGC pipelines, and the attribution-first approach ("Get Credited") aligns with EU creator rights frameworks. The same provenance model could extend to stills, audio, and documents.

[GitHub repository](#)

---

## Tide Shift

![Tide Shift](gifs/tideshift.gif)

*Collective migration from surveillance capitalism to digital freedom.*

Tide Shift solves the hardest problem in platform switching: nobody wants to be the first to leave. It uses a lobby-based coordination mechanic — users pledge to switch, and the migration only happens when a critical mass is ready. Nobody jumps alone.

**Why this is interesting:** Network lock-in is the primary reason surveillance capitalism platforms retain users who philosophically want to leave. Tide Shift makes the collective action problem visible and solvable by quantifying readiness ("1,256 people are ready to switch") and holding everyone in a lobby until the threshold is met. This is a genuinely novel migration mechanic with broad applicability — it could serve as the coordination layer for any community moving from Slack to Element, from WhatsApp to Signal, or from X to Mastodon.

[GitHub repository](#)

---

## Orbit

![Orbit](gifs/orbit.gif)

[Live preview](#)

*Discover people around you instantly.*

Orbit shows you who is physically nearby — within a configurable 10–50 metre radius — with names, avatars, and a short bio. A "Discover Mode" toggle gives full user control. The spatial map view makes serendipitous connection feel natural rather than intrusive.

**Why this is interesting:** Most proximity-based discovery apps are either dating-focused or require explicit check-ins. Orbit is context-neutral — equally useful at a conference, in a co-working space, at a festival, or in a neighbourhood. The adjustable radius and opt-in discover mode give it a privacy-first posture that distinguishes it from surveillance-adjacent location apps. The interaction model (you appear on others' maps only when you choose to) is a strong foundation for a European, consent-forward alternative to products like Foursquare Swarm or Zenly.

[GitHub repository](#)

---

## Homebase

![Homebase](gifs/homebase.gif)

[Live preview](#)

*App platform for building self-sovereign, secure, decentralized social applications.*

Homebase is a self-hosted identity and content layer. Users own their data (via Appwrite or similar backends), choose which social apps to connect, and carry their profile and posts across services. The demo shows a polished profile with Posts, Links, About, and Connections — all portable.

**Why this is interesting:** Homebase is a building block for the decentralized social web, but with a UX that looks and feels like a modern app rather than a developer tool. The RSS-style Follow button and portable identity model are directly compatible with ActivityPub and the broader Fediverse, while the Appwrite backend makes self-hosting accessible to non-technical users. This prototype demonstrates that data sovereignty doesn't have to mean technical sacrifice — and is a strong candidate for integration with European public digital infrastructure.

[GitHub repository](#)

---

## The Forest

![The Forest](gifs/theforest.gif)

[Live preview](#)

*Connect physically before digitally.*

The Forest requires you to touch phones with someone in person before a digital connection is made. Some connections can only be made in person — touch phones, share presence, discover kindred spirits. The app creates a gentle, atmospheric onboarding around the physical act of meeting.

**Why this is interesting:** The Forest inverts the standard social media paradigm: instead of collecting followers online and meeting them maybe in person, you must meet first. The phone-touch mechanic (using NFC or proximity) creates a physical ritual that anchors digital relationships in genuine encounter. This makes The Forest uniquely resistant to fake accounts and parasocial inflation — every connection in your network is someone you actually met. The model has obvious applications in event networking, education, and local community building, and aligns with growing interest in "offline-first" social design.

[GitHub repository](#)

---

## Personal Digest

![Personal Digest](gifs/personaldigest.gif)

[Live preview](#)

*Groups tuned by prominence to control how they rank in your feed.*

Personal Digest replaces the algorithmic feed with a user-controlled one. Each group or contact can be tuned for prominence — close friends loud, large communities quiet — resulting in a digest that reflects your actual priorities rather than an engagement-maximizing algorithm's.

**Why this is interesting:** The "Tune" mechanism is a lightweight but powerful intervention in feed design. By surfacing each group as a card and letting users dial its prominence, Personal Digest makes the hidden architecture of social feeds visible and controllable. This is a direct implementation of the "human-readable algorithm" concept that regulators and researchers have called for under the EU Digital Services Act. The design also demonstrates that feed transparency doesn't require complexity — the tuning metaphor is immediately intuitive.

[GitHub repository](#)

---

## Kirsten

![Kirsten](gifs/kirsten.gif)

[Live preview](#)

*AI mediated matchmaking and relationship coach.*

Kirsten is a voice-first AI agent that gets to know you through a warm, natural conversation — building your relationship profile without forms or questionnaires. The voice interface surfaces personality, communication style, and emotional intelligence in ways that text profiles cannot.

**Why this is interesting:** Most matchmaking apps are optimized for photos and text bios, which rewards presentation over substance and is trivially gameable. Kirsten's voice-first profile-building is a significant departure: a conversation can capture nuance, warmth, hesitation, and humour that a fill-in-the-blank form never could. The AI mediation layer also opens possibilities for ongoing relationship coaching — not just connecting people, but helping them communicate better. The model is reusable wherever nuanced human profiling matters: hiring, mentorship, therapy referral, or community building.

[GitHub repository](#)

---

## Wisdom Panel

![Wisdom Panel](gifs/wisdompanel.gif)

[Live preview](#)

*Where generations meet.*

Wisdom Panel is a structured intergenerational exchange: young people ask life's big questions, and experienced elders answer. The interface is deliberately minimal — no likes, no followers, just questions and responses, organized by newest and most answered.

**Why this is interesting:** As nuclear families fragment and mentorship networks thin, Wisdom Panel addresses a genuine social deficit: access to hard-won life experience. The dual-entry design ("Ask a question" / "Share your wisdom") respects both sides of the exchange. The absence of engagement mechanics (no likes, no follower counts) removes the incentive to perform and encourages honest, considered responses. This model has strong potential for integration with senior care networks, educational institutions, and civic organizations across Europe — and the Danish-language implementation shown in the demo suggests easy localization.

[GitHub repository](#)

---

## The Self

![The Self](gifs/theself.gif)

[Live preview](#)

*A resurrected symposium just for you.*

The Self is a philosophical AI symposium. You pose a question, and a gathering of AI-voiced "thinkers" debates it in real time — with marginal notes appearing alongside as the conversation develops. The aesthetic is parchment, classical typography, and genuine intellectual weight.

**Why this is interesting:** The Self reimagines AI conversation not as a chatbot but as a salon. The multi-voice model creates productive disagreement and nuance that single-model responses rarely achieve. The marginal notes UI is a design innovation — it separates the evolving argument from meta-commentary, a structure with roots in scholarly annotation traditions. Beyond personal use, this model is highly transferable to deliberative democracy tools, civic consultation platforms, and educational contexts where structured, multi-perspective debate is valued over consensus manufacturing.

[GitHub repository](#)

---

## Simple Meet

![Simple Meet](gifs/simplemeet.gif)

[Live preview](#)

*The doodle that actually works.*

Simple Meet creates a scheduling poll in under a minute — no login, no app download, mobile-first. Share the link, people mark their availability, done. It strips group scheduling back to the absolute minimum required to get a time agreed.

**Why this is interesting:** Doodle is widely resented for dark patterns, paywalls, and visual clutter, yet the underlying job-to-be-done — find a time that works for everyone — remains completely unsolved by anything simpler. Simple Meet's "free, no login, mobile-first" proposition is a direct answer to this frustration, and a reminder that the best product is sometimes the one that does less better. The no-login architecture is worth examining for any European civic tech context where low-friction participation is essential: community meetings, school scheduling, volunteer coordination.

[GitHub repository](#)

---

## The Concierge

![The Concierge](gifs/concierge.gif)

[Live preview](#)

*A concierge layer for group messaging.*

The Concierge sits above your message threads and tells you what actually needs your attention. Across groups of any size — from a best friend to a 1,043-member community — it surfaces unanswered questions, missed polls, pending decisions, and active threads, so you never have to scroll to catch up.

**Why this is interesting:** Messaging overload is one of the biggest friction points in modern social life, and most platforms respond by adding more notifications rather than smarter filtering. The Concierge flips this: rather than alerting on activity, it categorizes what *requires action*. The tagging system ("Brunch Sunday?", "Confirm Saturday 7pm", "Missed poll") is an interaction model that could fundamentally change how large community chats feel to casual members. This is directly applicable to platforms like Signal, WhatsApp, or any European messaging alternative looking to retain users in high-volume group contexts.

[GitHub repository](#)

---

## Sovereignty Planner

![Sovereignty Planner](gifs/sovereigntyplanner.gif)

[Live preview](#)

*Map your path away from big tech.*

Sovereignty Planner is a step-by-step migration guide from Big Tech lock-in to digital independence. Starting with hardware (because your device determines which OS and software you can run), it walks you through replacements for every layer of your digital life, with a filterable view across US lock-in, global, and European alternatives. Plans are exportable.

**Why this is interesting:** Most digital sovereignty guides are either overwhelming (a 200-item spreadsheet) or underspecified (a blog post saying "use Linux"). Sovereignty Planner's hardware-first, dependency-aware structure reflects how migrations actually fail in practice — you can't switch to European cloud storage if your OS doesn't support it. The "I HAVE → I WANT" journey framing, combined with an exportable plan, makes the switch feel achievable. This is directly usable as a tool for European governments, public institutions, and companies looking to reduce strategic dependence on non-European platforms.

[GitHub repository](#)

---

## DOGMAs

![DOGMAs](gifs/dogmas.gif)

[Live preview](#)

*Friction dogma #1: backwards typing.*

DOGMAs is a platform built around designed friction. The first dogma: you type your messages backwards — the letters appear in reverse as you write — and are displayed forwards to the recipient. A 15-second send delay adds a further pause for reflection. The result: slower, more intentional communication.

**Why this is interesting:** Most social platform design optimizes for speed and volume. DOGMAs inverts this as a conscious philosophical stance, making the act of writing require genuine attention. The backwards-typing mechanic is disorienting enough to break autopilot without being so frustrating that communication becomes impossible — a carefully calibrated friction that encourages you to mean what you say. This "friction as feature" design principle is broadly reusable: send delays, forced previews, and deliberate slowdowns are an underexplored design space with potential in mental health tech, deliberative discourse, and anti-harassment tooling.

[GitHub repository](#)

---

## Commons

![Commons](gifs/commons.gif)

[Live preview](#)

*Vibecoded community platform.*

Commons lets you describe your community in plain language and builds the right digital space for it. "We are a hiking group that plans trips together" generates a tailored set of modules — event planning, discussion, photo sharing — without manual configuration. Your existing spaces are shown as a dashboard of named communities.

**Why this is interesting:** Community platform setup is a known barrier to adoption — most people give up before they've created their first channel. Commons removes this entirely: describe the group, get the space. The AI scaffolding layer means every community gets a configuration appropriate to its purpose rather than a generic blank template. This is a promising architecture for civic tech, local government community engagement, neighbourhood platforms, and European alternatives to Facebook Groups — any context where the person creating the space is not a technical user.

[GitHub repository](#)

---

## Local Sports Finder

![Local Sports Finder](gifs/localsports.gif)

[Live preview](#)

*Pick up a game anywhere near you.*

Local Sports Finder shows you informal games and pickup sessions happening nearby right now. You select the sports you play in onboarding, and the app surfaces opportunities to join — football, basketball, tennis, padel, cycling, and more — removing the coordination friction that stops spontaneous sport from happening.

**Why this is interesting:** Informal sport is one of the most health-positive, socially connected activities available — and it's almost entirely unaddressed by social platforms. Finding a pickup game currently requires knowing the right WhatsApp group or being a regular at the right park. Local Sports Finder makes this discoverable to anyone. The sport-first matching (rather than friend-first) means you encounter a genuinely diverse social mix, and the physical activity context creates natural, low-stakes social connection. There's a clear policy angle here too: this is exactly the kind of platform European health ministries and municipalities should want to exist.

[GitHub repository](#)

---

## Craft

![Craft](gifs/craft.gif)

[Live preview](#)

*Share what you build.*

Craft is a maker-focused social platform for people who create physical things. Onboarding asks you to pick a primary hobby — DIY & Maker, Cooking & Baking, Photography, Painting & Art, Gardening, and more — and builds a personalized feed of made things around it. The emphasis is on the process and the object, not the creator's persona.

**Why this is interesting:** Mainstream social platforms are optimized for personality and performance — makers who post their projects are constantly competing with lifestyle content and personal branding. Craft's object-first design centres the thing made, not the person making it. This creates a fundamentally different social dynamic: you're appreciated for what you build, not how you present yourself. The model is reusable across any craft-adjacent platform — repair culture, open hardware, traditional crafts — and aligns naturally with European maker communities and circular economy initiatives that want to celebrate making and repair over consumption.

[GitHub repository](#)

---

## Tool Pool

![Tool Pool](gifs/toolpool.gif)

[Live preview](#)

*Find tools from neighbours. Reduce waste, save money, build together.*

Tool Pool is a hyperlocal tool lending network. An AI-powered search lets you describe what you need ("I need a drill for hanging shelves"), and the app surfaces tools available from nearby neighbours. Gamification (XP levels, "12 tools lent — keep going!") encourages lending, and community projects and repair workshops are surfaced alongside individual tools.

**Why this is interesting:** The average power drill is used for 12–15 minutes over its lifetime. Tool Pool addresses the absurdity of everyone owning their own rarely-used tools by making neighbourhood lending frictionless. The AI natural-language search removes the barrier of knowing exactly what tool you need, which is genuinely useful for non-experts. The XP/gamification mechanic is a smart way to build reciprocity norms without requiring social trust upfront. Beyond tools, this model applies to any underutilized physical asset — bikes, camping gear, kitchen equipment — and fits naturally within European circular economy policy frameworks and community resilience initiatives.

[GitHub repository](#)
