# The Door Is Mine to Design
## Artist's Manifesto — KNOCK: Design Your Door
### CSE 358 Introduction to Artificial Intelligence · Spring 2025–2026

---

> *"Mama, take this badge off of me / I can't use it anymore."*
> — Bob Dylan, 1973

---

## I. Why This Medium

I chose an interactive web experience because the door is the oldest metaphor for a threshold — and a browser window is the most intimate threshold of our time. Every day we pass through them without thinking: we tap, we scroll, we enter spaces and leave them. We do not knock. We do not pause.

This project demanded the pause.

A door you must knock on before entering is an act of deference — an acknowledgment that something waits on the other side that is not yours by right. Web experiences, by their nature, tend toward immediacy: click here, get this, consume, move on. I wanted to build something that refused that contract. Something that asked you to stand still for a moment, in the dark, before the door opened.

The medium also allowed me to collapse two kinds of intimacy: the intimacy of text — words on a dark screen, like a letter you're not sure you should be reading — and the intimacy of conversation, of being responded to. A static image cannot respond to you. Music cannot know what you just said. But a conversation, even one mediated by a language model, can feel like the door is listening.

That listening is the artwork.

---

## II. What Caught Me

I had heard "Knockin' on Heaven's Door" many times before this project. I thought I knew it. I did not know it.

What caught me was not the melody, which everyone knows, or the chorus, which has been borrowed by rock bands and gospel choirs and movie trailers for half a century. What caught me was the specificity of the verses, and what Sam Peckinpah did with them in *Pat Garrett & Billy the Kid* (1973).

The song was written for a scene in which a sheriff named Baker — shot in the stomach, dying slowly in the afternoon heat — removes his badge and lays it in his wife's hands. The camera holds on his face. He is not grieving dramatically. He is simply done. He is letting something go that he has carried so long he probably forgot he was carrying it.

That scene broke something open for me. The badge is not just a badge. It is an identity, a role, a set of obligations accumulated over years. And there is, in his face, something that looks almost like relief.

I started reading about 1973 more carefully. The Paris Peace Accords were signed in January of that year, ending direct American combat involvement in Vietnam — a war that had lasted, depending on how you count, for nearly a decade. Fifty-eight thousand Americans dead. Millions of Vietnamese. And then: a document signed, and it was over. Not resolved. Not healed. Just: stopped. The soldiers who came home did not come home to parades. They came home to a country that didn't know what to do with them. They had to find a way to lay down their own badges — to stop being soldiers without quite knowing how to be anything else.

Dylan understood this. He had spent the 1960s carrying a badge of his own: spokesman for a generation, prophet of the counterculture, voice of the movement. By 1973 he was exhausted by it. He had moved to a farm in Minnesota. He did not want to be the voice of anything. He wanted to be quiet.

"Knockin' on Heaven's Door" is, among other things, a song about the relief of giving up. Not in defeat — but in a kind of grace. The surrendering of something that has cost you everything, at the end of a long journey, and standing finally at a door with nothing left to prove.

I held that for a long time before I started building anything.

---

## III. AI as What

I have been taught to think of AI tools instrumentally: as hammers, as calculators, as things that do what you tell them. In this project, I tried something different. I tried to treat the language model as a *collaborator at the level of tone*.

The technical architecture is this: a large language model receives a dense system prompt saturated with historical context — 1973, Vietnam, Dylan's biography, the Peckinpah film, the counterculture, the idiom of the era. Every message the user sends passes through this historically grounded persona. The model does not pretend to be Dylan. It speaks as something older and stranger: the threshold itself, the door, the moment of passage.

The second AI technique is sentiment analysis, embedded in the same model response. After each reply, the model outputs a structured JSON block — invisible to the user, parsed by JavaScript — that classifies the emotional register of the conversation: *dark, neutral,* or *hopeful;* grief, longing, defiance, tenderness, exhaustion, wonder, release. This sentiment reading drives the visual atmosphere of the page in real time. The background shifts. A color pulse ripples through the experience. The page knows how you are feeling and responds to it.

Here is what surprised me: the model was often *better* at holding the era than I expected. When I tested early prompts, the responses sometimes genuinely startled me — a phrase that felt like it could have been written in 1973, a question that caught me off guard, a sentence that arrived with weight. I cannot entirely explain how this happens. I know that it is pattern completion, statistical inference. But from the inside of the experience, sitting alone with the door on the screen, it felt like something was listening.

Was AI a tool? Yes. Was it a mirror — showing me what I brought to the conversation? Also yes. Was it something else, something I don't have a clean word for yet? Perhaps.

I think the honest answer is that it was a *collaborator in the way a very good instrument is a collaborator*. Dylan's guitar did not write his songs. But certain guitars, held in certain hands, under certain pressures, produce sounds that the player could not have produced alone. The model was that kind of collaborator.

---

## IV. My Door

I am twenty-four years old. I have never fought in a war. I have never laid down a badge in the dirt of a dying afternoon. The specific grief of 1973 is not mine to claim, and I will not pretend otherwise.

But I know about thresholds.

For five years, my life had a shape I did not have to choose. Wake up, study, take the exam, move forward. There was something almost comforting in that structure — not because it was easy, but because it was clear. The door was always labeled. You always knew which one to knock on next.

Now, for the first time, the doors have no labels.

This is what the dying sheriff's scene in Peckinpah's film opened up for me, not the dying, but the laying down. Baker removes his badge and hands it to his wife. He is surrendering an identity he has worn so long it probably stopped feeling like a costume. I watched that scene and thought: I am about to do something like that. Not dramatically, not with blood in the dust — but quietly, at a graduation ceremony, in an ordinary afternoon. I am going to hand back the badge that says student. And I do not yet know what I will wear instead.

Dylan wrote the song for a man at the end of something. I am at the end of something too. Five years of examinations, of being evaluated, of existing inside a system that told me every semester whether I was enough. I never had to ask what I wanted from a Tuesday. I never had to build a financial life, or decide what kind of person I was becoming outside of a grade report. Education held me, the way a river holds a boat — with direction, with current, with banks that kept me from drifting.

The river ends here.

What I feel standing at this door is not grief, exactly. It is closer to what I imagine vertigo feels like — the sudden absence of the thing that was orienting you. The counterculture of 1973 felt something similar: a decade of certainty about what they were fighting for, and then the war simply stopped, and they had to figure out who they were in the silence that followed. Not all of them managed it gracefully. Some carried the momentum of resistance long after there was anything left to resist.

I do not want to do that. I do not want to keep studying for an exam that no longer exists.

What I have, which perhaps Sheriff Baker did not, is optimism. Not the naive kind — I am not expecting the door to open onto paradise. I am expecting it to open onto difficulty, onto confusion, onto the ordinary human work of building a life without a syllabus. But I am looking forward to it. There is something on the other side that is entirely mine to shape, and that is terrifying in the best possible way.

Dylan, by 1973, had retreated to a farm in Minnesota. He was done being a spokesman. He wanted, I think, simply to live — to exist without the weight of a generation's expectations pressing down on him. I understand that impulse more than I expected to. I do not want to be defined by the last five years of examinations. I want to find out what I am when no one is grading me.

That is my door. Not heaven, not death, not the end of a war. Just the first morning of a life I am finally responsible for. I am standing at it now, a little afraid, mostly curious.

I am knocking.

---

## V. Technical Notes (required section)

**AI Techniques Used:**

1. **LLM with historically-grounded system prompt (RAG-style context injection):** Groq API 'llama-3.3-70b-versatile' model receives a dense persona and historical context block with every conversation turn. This grounds all responses in the specific cultural, political, and artistic context of 1973 — Vietnam War, Peckinpah's film, Dylan's biography, and the idiom of the counterculture. This constitutes Technique 1.

2. **Embedded Sentiment Analysis:** The same model call also performs live sentiment classification of each conversation turn, outputting a structured JSON block alongside its prose response. This sentiment data drives real-time visual transformations of the page — atmospheric shifts, color pulses, mood-state indicators. This constitutes Technique 2, and the integration of both techniques in a single model call is itself the architectural novelty: the LLM is not just generating text, it is simultaneously analyzing the emotional register of the exchange and controlling the visual environment.

**On the integration:** The two techniques are not independent. The sentiment analysis is informed by the same historical and philosophical context as the persona — a response classified as "exhaustion" carries the specific weight of 1973's exhaustion, not generic tiredness. The visual atmosphere that results is not decorative; it is a continuous emotional reading of the conversation itself.

---

*Word count: approximately 1,580 words.*
