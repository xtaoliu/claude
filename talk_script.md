# Talk script: From Event Language to Relational Learning

About 13 minutes, 11 slides. The same numbered points are in the PowerPoint speaker notes.

## Slide 1. Title  (0:00–0:30)

1. Thank you for having me.
2. I will show how my work on event language in adults and children leads to the question I want to pursue in your group.
3. That question is how language helps children learn relations.

## Slide 2. One question across my work  (0:30–1:15)

1. Mandarin gives a clean contrast: cā names only the action; cā-gānjìng names the action and its result.
2. My work asks whether this kind of difference matters for cognition.
3. Study 1 is my PhD on adults; Studies 2 and 3 are on children’s language.
4. Then three directions that grow out of the thesis.

## Slide 3. Study 1 (PhD)  (1:15–3:45)

1. Question: does how a language encodes events align with how speakers process them? English and Mandarin speakers saw 44 matched videos of the same object being cut or blended; cutting has a clear endpoint, blending does not.
2. The contribution is separating two levels of encoding. At the lexical level, English marks the object with quantized nouns (68% vs. 13%) and Mandarin marks the result with resultatives, mostly for blending (44% vs. 17%). At the predicate level, English is more telic for cutting (79% vs. 51%), Mandarin for blending.
3. Each level has its own processing measure, and the effect appears where that level’s contrast is. Lexical level and interruption detection: in blending, English speakers caught early interruptions better, Mandarin speakers late ones (p = .040). Predicate level and boundary tapping: in cutting, Mandarin speakers placed the end 862 ms later (p = .005), with no difference at onset.
4. Experiments 4 and 5 added brief lexical and telicity primes. Group differences recurred, but primes did not shift either level (Bayes factor about 1000 for the null). So the link is stable but not created by a one-off cue, which motivates looking at learning and development.

## Slide 4. Study 2  (3:45–5:00)

1. Children often reject “she peeled the lychee” when the lychee is not open, more than adults do. The question is why.
2. We filmed 10 action pairs that share an object and a result, each with the result attained or not; 32 four-year-olds, 32 five-year-olds and 40 adults per experiment judged and described them.
3. Our proposal: how strongly a verb implies its result depends on the action–object–result relation, not only on the verb. Peeling very likely opens a lychee (rated 93); squeezing less so (65). Stronger association should mean more rejection when the result is absent.
4. [Main result here, or: data are collected and analysis is in progress.] This study gives me experience testing children in kindergartens and materials I can reuse.

## Slide 5. Study 3  (5:00–5:45)

1. This sole-authored corpus study, at minor revision in Language and Cognition, tests the pragmatic-informativeness account of superordinate nouns (Choe & Papafragou). Words like “animal” are under-informative, so in English they appear in contexts that signal generality: plurals, quantifiers, wh-phrases, “kind of”, “another”.
2. Mandarin has no obligatory plural, so it separates two versions of the account. If the cues are a fixed English form that depends on plurals, the contrast should weaken. If they reflect a shared communicative function, the remaining cues should still carry it.
3. Across 11 Mandarin CHILDES corpora, all four available contexts were associated with superordinates (odds ratios 2.1 to 8.2), robust to overlapping cues, and a classifier recovered the semantic level above chance (AUC = .73). So the cues reflect a shared function, not a fixed form.
4. But availability is not use: in both languages, corpus frequency predicted age of acquisition, while cue exposure added little. Whether children actually use these cues needs experiments, the same step from correspondence to learning that runs through my future plans.

## Slide 6. From the thesis to three questions  (5:45–6:30)

1. The thesis shows a correspondence between language and event processing in adults, but not where it comes from.
2. Question 1: when do these differences emerge in development? That is Direction 1.
3. Question 2: brief primes did not work, so can sustained language change processing? That is Direction 2.
4. Question 3: does text alone yield both levels of event encoding? Language models let us test that, Direction 3.

## Slide 7. Direction 1: Development  (6:30–8:15)

1. New event pairs address the main limit of the thesis: only cutting and blending, with instrument and motion confounded. Each pair is hands-only, on the same object, one with a clear endpoint and one gradual, for example tearing paper in half versus crumpling it. Each pair is normed and described by adults first, to confirm that the lexical and predicate contrasts fall on different events.
2. Mandarin- and English-speaking children aged 3–6; the English sample can build on the center’s cross-cultural partners.
3. Each child describes the events, which gives an individual profile at both levels: resultatives and quantized nouns at the lexical level, telic descriptions at the predicate level. Processing uses child-friendly versions of my two tasks: press when the video “hiccups” for phases, press when it is “done” for endpoints; eye-tracking for the youngest children.
4. Crossed prediction: a child’s lexical encoding should predict phase sensitivity but not endpoints; predicate telicity should predict endpoints but not phases. That is a double dissociation at the individual level, which the thesis could not test. A 6-month follow-up asks whether language change comes before processing change.

## Slide 8. Direction 2: Training  (8:15–9:45)

1. In the thesis, brief primes did not shift processing. Direction 2 tests sustained training, keeping the two-level logic of Experiments 4 and 5 but crossing it.
2. Mandarin children are trained at one level, lexical cues (一颗, 切成两块) or predicate cues (切开 vs. 切一切), and tested on both tasks, interruption detection for phases and boundary tapping for endpoints.
3. Following the thesis conclusions: three sessions in which children use the words in the task, a check that they understood the cue, and counterbalanced baseline order.
4. Prediction: each training shifts only its own level. Training on one event family (撕 / 揉) and testing on another (掰 / 压) asks whether children learned an abstract endpoint relation rather than a word.

## Slide 9. Direction 3: Language models  (9:45–11:30)

1. The main contribution of my thesis is separating two levels of event encoding: local lexical cues (quantized nouns, resultatives) and whole-predicate telicity. Direction 3 asks whether language models separate them too.
2. Following Rognan, Grigoroglou and Bhattasali (CogSci 2026), I would treat matched monolingual models, English BERT and Chinese BERT, as test subjects in cloze tasks built from my stimuli, then extend to multilingual models and larger LLMs.
3. Lexical level: which determiner the model predicts in “She cut [MASK] orange”, and which result complement in 他把橙子搅[MASK]了, for cutting versus blending verbs. Predicate level: “in” versus “for” in “cut an orange [MASK] two seconds”, and whether the model allows cancellation in 他切了橙子，但是[MASK].
4. Key test: does the predicate-level choice flip when the lexical cue flips (an orange vs. oranges; 切开 vs. 切)? If models match humans at the lexical level but not the predicate level, they rely on surface statistics rather than event structure. Model scores are compared with my Exp 1 descriptions and the adult and child data.

## Slide 10. A two-year plan  (11:30–12:15)

1. Year 1: replicate Experiments 1–3 with adults on the new event pairs, which generalizes the thesis and validates materials for children; run the model study in parallel.
2. Year 2: Direction 1 with children, and the training study for Direction 2.
3. Throughout: publish the thesis papers, apply for funding, and mentor students.
4. Together these move from correspondence to development, learning and input.

## Slide 11. What I would bring  (12:15–13:00)

1. Methods: video stimuli, child testing, Bayesian modelling.
2. Projects: I led a field project at CAS and ran a preregistered multi-experiment thesis.
3. Fit: event language in development, Mandarin–English expertise, and both experiments and models.
4. Thank you, and I am happy to take questions.
