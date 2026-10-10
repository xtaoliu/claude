# Talk script: From Event Language to Relational Learning

About 13.5 minutes, 13 slides. The same numbered points are in the PowerPoint speaker notes.

## Slide 1. Title  (0:00–0:30)

1. Thank you for having me.
2. I will show how my work on event language in adults and children leads to the question I want to pursue in your group.
3. That question is how language helps children learn relations.

## Slide 2. One question across my work  (0:30–1:30)

1. Mandarin gives a clean contrast: cā names only the action; cā-gānjìng names the action and its result.
2. My work asks whether this kind of difference matters for cognition.
3. Part one: adults, in my PhD.
4. Part two: children, with Yue Ji. Part three: three directions that grow out of the thesis.

## Slide 3. PhD design  (1:30–2:30)

1. Matched videos of the same object being cut or blended.
2. Cutting has a clear endpoint; blending does not. Norming confirmed this.
3. Step 1: how speakers describe the events (20 English, 20 Mandarin).
4. Step 2: whether processing differs in the same direction (interruption detection 64 + 64; boundary tapping 20 + 20). Step 3: whether brief language cues can shift it (60 + 60; 36 + 36).

## Slide 4. Exp 1  (2:30–3:30)

1. Telicity shows a crossover: English is more telic for cutting (79% vs. 51%), Mandarin for blending (44% vs. 17%).
2. English speakers mark the object with quantized noun phrases (68% vs. 13%).
3. Mandarin speakers use resultatives for blending (44% vs. 17%).
4. So the languages differ at two levels: the lexical level and the whole predicate. This two-level distinction is the main contribution of the thesis.

## Slide 5. Exp 2–3  (3:30–4:45)

1. Interruption detection: English speakers caught early interruptions in blending better, Mandarin speakers late ones (χ²(2) = 6.46, p = .040).
2. This mirrors object marking versus result marking.
3. Boundary tapping: English speakers ended cutting events near the physical endpoint, Mandarin speakers almost a second later (95% CI [−1455, −268] ms).
4. This matches the stronger English telicity for cutting.

## Slide 6. Exp 4–5  (4:45–5:45)

1. Part of the cross-linguistic pattern replicated.
2. The preregistered priming predictions were not supported; the Bayes factor favours the null for the key interaction.
3. So the link is real, but a one-off cue does not produce it.
4. If language shapes event representation, it more likely does so over time, through learning.

## Slide 7. Children  (5:45–7:00)

1. Children often reject “she peeled the lychee” when it is not open, more than adults do.
2. We propose this depends on the specific action–result relation: peeling very likely opens a lychee, squeezing less so.
3. Ten matched pairs, 40 videos; 32 four-year-olds, 32 five-year-olds and 40 adults per experiment; adult ratings of likelihood and typicality as predictors.
4. [Main result here, or: data are collected and analysis is in progress.] So I already test children on action–result events, with videos and ratings I can reuse.

## Slide 8. From the thesis to three questions  (7:00–7:45)

1. The thesis shows a correspondence between language and event processing in adults, but not where it comes from.
2. Question 1: when do these differences emerge in development? That is Direction 1.
3. Question 2: brief primes did not work, so can sustained language change processing? That is Direction 2.
4. Question 3: does text alone yield both levels of event encoding? Language models let us test that, Direction 3.

## Slide 9. Direction 1: Development  (7:45–9:15)

1. New event pairs address the main limit of the thesis: only cutting and blending, with instrument and motion confounded. Each pair is hands-only, on the same object, one with a clear endpoint and one gradual, for example tearing paper in half versus crumpling it. Each pair is normed and described by adults first, to confirm that the lexical and predicate contrasts fall on different events.
2. Mandarin- and English-speaking children aged 3–6; the English sample can build on the center’s cross-cultural partners.
3. Each child describes the events, which gives an individual profile at both levels: resultatives and quantized nouns at the lexical level, telic descriptions at the predicate level. Processing uses child-friendly versions of my two tasks: press when the video “hiccups” for phases, press when it is “done” for endpoints; eye-tracking for the youngest children.
4. Crossed prediction: a child’s lexical encoding should predict phase sensitivity but not endpoints; predicate telicity should predict endpoints but not phases. That is a double dissociation at the individual level, which the thesis could not test. A 6-month follow-up asks whether language change comes before processing change.

## Slide 10. Direction 2: Training  (9:15–10:45)

1. In the thesis, brief primes did not shift processing. Direction 2 tests sustained training, keeping the two-level logic of Experiments 4 and 5 but crossing it.
2. Mandarin children are trained at one level, lexical cues (一颗, 切成两块) or predicate cues (切开 vs. 切一切), and tested on both tasks, interruption detection for phases and boundary tapping for endpoints.
3. Following the thesis conclusions: three sessions in which children use the words in the task, a check that they understood the cue, and counterbalanced baseline order.
4. Prediction: each training shifts only its own level. Training on one event family (撕 / 揉) and testing on another (掰 / 压) asks whether children learned an abstract endpoint relation rather than a word.

## Slide 11. Direction 3: Language models  (10:45–12:15)

1. The main contribution of my thesis is separating two levels of event encoding: local lexical cues (quantized nouns, resultatives) and whole-predicate telicity. Direction 3 asks whether language models separate them too.
2. Following Rognan, Grigoroglou and Bhattasali (CogSci 2026), I would treat matched monolingual models, English BERT and Chinese BERT, as test subjects in cloze tasks built from my stimuli, then extend to multilingual models and larger LLMs.
3. Lexical level: which determiner the model predicts in “She cut [MASK] orange”, and which result complement in 他把橙子搅[MASK]了, for cutting versus blending verbs. Predicate level: “in” versus “for” in “cut an orange [MASK] two seconds”, and whether the model allows cancellation in 他切了橙子，但是[MASK].
4. Key test: does the predicate-level choice flip when the lexical cue flips (an orange vs. oranges; 切开 vs. 切)? If models match humans at the lexical level but not the predicate level, they rely on surface statistics rather than event structure. Model scores are compared with my Exp 1 descriptions and the adult and child data.

## Slide 12. A two-year plan  (12:15–13:00)

1. Year 1: replicate Experiments 1–3 with adults on the new event pairs, which generalizes the thesis and validates materials for children; run the model study in parallel.
2. Year 2: Direction 1 with children, and the training study for Direction 2.
3. Throughout: publish the thesis papers, apply for funding, and mentor students.
4. Together these move from correspondence to development, learning and input.

## Slide 13. What I would bring  (13:00–13:45)

1. Methods: video stimuli, child testing, Bayesian modelling.
2. Projects: I led a field project at CAS and ran a preregistered multi-experiment thesis.
3. Fit: event language in development, Mandarin–English expertise, and both experiments and models.
4. Thank you, and I am happy to take questions.
