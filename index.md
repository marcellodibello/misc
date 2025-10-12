
*RWL = Read Watch Later*


# Oct 12, 2025

## AI, understanding and causality  

- (RWL) Mark Bishop, [Artificial Intelligence is stupid and causal reasoning won't fix it](https://arxiv.org/abs/2008.07371)

> Abstract: Artificial Neural Networks have reached Grandmaster and even super-human performance across a variety of games: from those involving perfect-information (such as Go) to those involving imperfect-information (such as Starcraft). Such technological developments from AI-labs have ushered concomitant applications across the world of business - where an AI brand tag is fast becoming ubiquitous. A corollary of such widespread commercial deployment is that when AI gets things wrong - an autonomous vehicle crashes; a chatbot exhibits racist behaviour; automated credit scoring processes discriminate on gender etc. - there are often significant financial, legal and brand consequences and the incident becomes major news. As Judea Pearl sees it, the underlying reason for such mistakes is that, 'all the impressive achievements of deep learning amount to just curve fitting'. The key, Judea Pearl suggests, is to replace reasoning by association with causal-reasoning - the ability to infer causes from observed phenomena. It is a point that was echoed by Gary Marcus and Ernest Davis in a recent piece for the New York Times: 'we need to stop building computer systems that merely get better and better at detecting statistical patterns in data sets - often using an approach known as Deep Learning - and start building computer systems that from the moment of their assembly innately grasp three basic concepts: time, space and causality'. In this paper, foregrounding what in 1949 Gilbert Ryle termed a category mistake, I will offer an alternative explanation for AI errors: it is not so much that AI machinery cannot grasp causality, but that AI machinery - qua computation - cannot understand anything at all.

From the abstract, it seems a good overview and perhaps a nice introductio into disputes about AI. Three key paradigms:
1. AI as machine learning, curve fitting, regression (deep learning, a sophisticated version of that)
2. AI based on causal knowledge, time and space (Marcus, Pearl)
3. AI as developing true understanding (see Searle's Chinese room argument)

- (RWL) [video discussion](https://www.youtube.com/watch?v=e1M41otUtNg) on the paper, as well.

## Google Deep Mind Tim Nguyen and Varufakis

[Tim Nguyen](https://timothynguyen.org/) is a prominent deep learning scientist at Google Deep Mind. He was in a debate on AI and capitalism with Varufakis. 

Varufakis said: we need Google serches, weed need AI for the betterment of humanity. Thus, we need to socialize Goodle and AI. 

Nguyen had no answer!

See [video](https://www.youtube.com/watch?v=5dMIuCdLL7Y)

## The Chinese Room coming back

What's also striking is that Nguyen, in a [blog post](https://timothynguyen.org/2025/08/21/a-summer-of-ai-debates-and-talks/), reports of a conversatio with Mark Bishop and he writes:

> I found myself in a prolonged discussion with Mark Bishop, who was quite pessimistic about the capabilities of large language models. Drawing on his expertise in theory of mind, he adamantly claimed that LLMs do not understand anything – at least not according to a proper interpretation of the word “understand”. While Mark has clearly spent much more time thinking about this issue than I have, I found his remarks overly dismissive, and we did not see eye-to-eye.

> However, a fruitful outcome of our discussion was his suggestion that I read John Searle’s original Chinese Room argument paper. Though I was familiar with the argument from its prominence in scientific and philosophical circles, I had never read the paper myself. I’m glad to have now done so, and I can report that it has profoundly influenced my thinking – but the details of that will be for another debate or blog post

Interesting. Philosophy is not so useless then! It is odd that Tim Nguyen who works at Google Deep Mind had to wait until 2025 to be influenced by Searle's paper! And it is odd that he had no response to Varufakis point about the socialization of AI. 

## n-gram models and LLMs

- (RWL) Timothy Nguyen - [Understanding Transformers via N gram Statistics](https://www.youtube.com/watch?v=tf4ZLcQBu1g)

## Intro discussion to AI, LLMs etc.

- (RWL) [How Does AI Work?](https://www.youtube.com/watch?v=OQXiOpG1Y1s&t=45s) | Robert Wright & Timothy Nguyen

- Word2Vec, simple mapping from words to vectors in several dimensions
- transformer, more complex mapping that can take into account context, semantic ambiguity 



# Feb 20, 2025

## Causal strcture and normative committments

Typically we think of the causal structure of the world as objective, to be investigated with data and evidence, and in any way distinct from normative questions. Well, that assumption seems incorrect. The case of race and gender---and claims of wrongoful discrimination---is an example. The work of Lily Hu is the key reference here.

- (RWL) Hu (2024), [Normative Facts and Causal Structure]()

> This article challenges the widespread view that causal relations are wholly non-normative natural relations. In the case of salient social categories such as race and sex, I argue for a dependency of the causal order of things on the moral and political. At the center of my argument is a puzzle about how audit studies, social scientific experiments that approximate the idealized controlled experiment, work to probe the causal significance of race and sex. Essential to these studies is the distinction between differences that constitute rather than confound an effect of their variable of interest—a distinction, which, I claim, embodies judgments about the sorts of differences that constitute the wrongful causal influence of these categories. If our best scientific practices latch onto genuine features of causation, then normative theorizing’s place in scientific causal theorizing entails that normative facts figure in the causal structure.

But there seems to be other domain where  causality and normativity are intertwined,  debates about alternative energies or actual causation:

- (RWL) Statham (2020), [Normative commitments, causal structure, and policy disagreement](https://philpapers.org/rec/STANCC)

> Recently, there has been a large amount of support for the idea that causal claims can be sensitive to normative considerations. Previous work has focused on the concept of actual causation, defending the claim that whether or not some token event c is a cause of another token event e is influenced by both statistical and prescriptive norms. I focus on the policy debate surrounding alternative energies, and use the causal modelling framework to show that in this context, people’s normative commitments don’t just affect the causal claims they are willing to endorse, but also their understanding of the causal structure. In the context of the alternative energy debate, normative considerations affect our understanding of the causal structure by influencing our judgements about which variables should be held fixed, and therefore which variables should be relegated to the background of a causal model. In cases of extreme disagreement, normative commitments can also affect which causal structure we think should be instantiated. Thus, focusing on a new context has revealed a previously unexplored sense in which normative factors are incorporated into causal reasoning.



## Bostock v. Clayton County (2020)

Going back to the landmark Sup. Ct. decision on discrimination on the basis of sexual orientation and being transgender (SOT for short). [Bostock v. Clayton County (2020)](https://www.oyez.org/cases/2019/17-1618). While these expressions are not explicitly present in Title VII, the Court held that discrminating on the basis of SOT is discrmination on the basis of sex, and thus prohibited by Title VII. The test for discrimination based on sex in the emplyment context is this:

> If the employer intentionally relies in part on an individual employee’s sex when deciding to discharge the employee—--put differently, if changing the em­ployee’s sex would have yielded a different choice by the em­ployer---a statutory violation has occurred.

Note the but-for causation counterfactual test: had the employee been of a different sex, would have they been differently treated (fired/hired) by the emplyoer? If yes, a violation of Title VII has occurred.

Now here is the key passage:

> it is impossible to discriminate against a person for being homosexual or transgender without discriminating against that individual based on sex. Consider, for example, an employer with two employees, both of whom are attracted to men. The two individuals are, to the employer’s mind, materially identical in all respects, except that one is a man and the other a woman. If the employer fires the male employee for no reason other than the fact he is attracted to men, the employer discriminates against him for traits or actions it tolerates in his female colleague. Put differently, the employer intentionally singles out an employee to fire based in part on the employee’s sex, and the affected employee’s sex is a but-for cause of his discharge.

The way I understand this is by running the appropriate counterfactual test for but-for causation. The two employees are indistinguishable---they both like men, equally qualified, etc.---but one is male (and thus homosexual) and the other female (thus heterosexual). If the male emplyoee is fired because of their sexual preference towards men, then had they been female they would not have been fired (since their sexual preference towards men would not be problematic). So, being fired becaue of sexual preference towards men (discrimination based on sexual preference) implies being fired because of being man (discriminatiom based on sex).

> Or take an employer who fires a transgender person who was identified as a male at birth but who now identifies as a female. If the employer retains an otherwise identical employee who was identified as female at birth, the employer intentionally penalizes a person identified as male at birth for traits or actions that it tolerates in an employee identified as female at birth. Again, the individual employee’s sex plays an unmistakable and impermissible role in the discharge decision.

In the transgender case the reasoning seems similar. The two employees are identical except that one identifies as female at birth while the other transitioned from male to female. If the employer fires the latter, but would not have fired the former, this means that had the emplyoee being female (at birth), they would not have been fired. So, again discrimination based on transgenderism is also discrimination based on sex. 

## Connecting with Hu's work

I wonder what Lily Hu's vignettes have to say about that? Here is one case from her 2022 dissertation:

> AUDIT STUDY I: Skirt Interview - Two actors, one taken to be male and the other female, present identical resumes, answer interviewer questions identically, and affect the same tone, mannerisms, and general personality traits (as best as they can). The male actor also dons the same dress and wears the same facial makeup as the female actor; both actors wear skirts and facial makeup to their interviews. (p. 86)

Suppose one actor is hired but the other is not. Or suppose you can track the disparity across alike cases. So what is the cause of the decision?  It is sex/gender or something else? Hu seems to think, if I remember right, that it's not clear here whether the discrmination was because of sex/gender or because of failure to follow gender conforming rules. In fact, it's  likely that the discrimination was becaue of the gender rules, not sex/gender.  But a manipulationist account of causation -- keep everything the same, just change sex/gender -- would say that the cause here is sex/gender, not failure of conformity with gender norms. 

But, interestingly, the US Sup. Ct. does not find anything problematic here. The counterfactual test above says that Hu's case is a case of sex discrimination. 

## Because of sex v. because of gender non conformity

During the oral argument, the Justices talked about cases involving women behaving according to male gender norms or men behaving according to female gender norms. Some of the Justices seemed to think that, if these individuals were discriminated because of their gender non-conformity, they would be discriminated---at least in part---because of their sex/gender. Here is the lawyer Pamela S. Karlan, who was representing Bostock:

> I'm simply saying that if a man and a woman both wanted to sew and you fire the man who loves sewing and you don't fire the woman who loves sewing, that's discrimination pure and simple, sex discrimination.

So, there seems to be no issue that, if someone fails to conform with gender norms and they are discriminated because of that, they are also discriminated because of their sex/gender. Justice Alito, however, disagrees:

> The -- the point is that discrimination on the basis of sex in the sense that Congress understood it in 1964 is a different concept from discrimination on the basis of sexual orientation.

## The sex discrimination test in Bostock isn't logically sound 

A blog critical of the opinion came out right after. 

- [Analysis
Justice Gorsuch’s Misguided Sex Discrimination Opinion Fails Logic Test](https://www.dailysignal.com/2020/06/19/justice-gorsuchs-misguided-sex-discrimination-opinion-fails-logic-test/)

It gives good counterexamples:

> Suppose a female lifeguard is fired because she wears a swimsuit bottom but refuses to wear a top. No doubt, “changing the employee’s sex would have yielded a different choice by the em­ployer” and her sex was a “but-for” cause of the decision. Yet her termination was not sex discrimination provided it held males and females to the same standard: A male lifeguard who exposed private parts would have similarly been fired.

> Suppose a male employee at a fitness center repeatedly goes into the women’s locker room and is fired. Now it’s true that “changing the em­ployee’s sex would have yielded a different choice by the em­ployer” and that his sex was a “but-for” cause of the decision to fire him. But the negative treatment the employee faced was not sex discrimination provided the employer imposed no double standard for men and women, such as a bathroom policy that imposed the same burden on men and women: Each is prevented from entering the opposite sex’s private space.

So these seem to be good counterexamples. And it does not help to say that discrmination also requires harm. There is harm in this cases because the emplyoee is fired -- clearly a harm. But it is not a harm that, intuitively, can be traced back to sex. Male and females lifeguards are not differently harmed (fired) because of their sex.  

## Differential treatment that is unevenly harmful for people of different sexes

The author of the blog post offers an alternative:

> To be a case of sex discrimination, sex must not only be a “but-for” cause of differential treatment, but that differential treatment must also entail disadvantageous terms or conditions to which members of only one sex are subjected. The simplistic test that Gorsuch puts forth looks for the “but-for” cause and “negative” treatment, but it doesn’t link the two: It doesn’t look for disadvantages directed at individuals of only one sex. He’s offered half a theory of sex discrimination.

> The court in Oncale quoted Ginsburg to explain: “The critical issue, Title VII’s text indicates, is whether members of one sex are exposed to disadvantageous terms or conditions of employment to which members of the other sex are not exposed.”

Interesting decisions to read on sex discrimination:  

- (RWL)[Oncale v. Sundowner Offshore Services, Inc.](https://www.oyez.org/cases/1997/96-568) (1997)

- (RWL) [US v. Virgina](https://www.oyez.org/cases/1995/94-1941) (1996)
- 

## Kagan on Manhart and the simple counterfactual test

The simple but-for counterfactula test was apparently alrewayd set up in Manhart, a very old case. Women had to pay larger retirement contributions into tehir pension plan because statistically they lived longer. Was the discrmination beased on sex?

- (RWL)[City of Los Angeles Department of Water and Power v. Manhart, (1978)](https://www.oyez.org/cases/1977/76-1810)

In Manhart, a separate characteristic, longevity, is explicitly used as a reason for differential treatment, sex is not explicitly used for differential treatment. Justice Kagan during the oral argument in Bostock says:

> So all of these hypotheticals are really about the same thing, which is that Manhart gave us a very simple test, and Manhart said, what you do when you look to see whether there is discrimination under Title VII is, you say, would the same thing have happened to you if you were of a different sex? And, Ms. Karlan made all the -- you know, went through all the ways in which, obviously, the -- the same thing would not have happened to you if you were a different sex, you being her client. So, I mean, that's the question. There are independent characteristics in all these cases.

The case seems to be different. In Bostock, the differential treatment is explicitly due to gender identity, and the question is this: is it also differential treastment because of sex? In Manhart, the differential treatment is actually because of sex, plain and simple: women are asked to pay more into their plan. But a justification is given for that, namely differences in longevity. Manhart seems to be a different case to me!

So the lawyer on the other side, Jeffrey Harris, seems right:

>  ... employer made no attempt to do any sort of bona fide underwriting or life expectancy estimates.
It simply charged the women more. So even a woman and a man, if they each had a 75-year life expectancy, they would be charged different rates, even though they were totally, similarly situated with respect to that.

# Feb 10, 2025

# Personalized law v precision medicine

We have personalized law, a new trend, though not so new perhaps. Legal rules tailored to individual, based on their needs, risk tolerance, metal capacities, etc. What are the ethical and legal implications of that? Does it make sense at all?

- (RWL) Chicago Law Review Symposium [Personalized Law: Different Rules for Different People](https://lawreview.uchicago.edu/series/personalized-law-different-rules-different-people)

- (RWL) Book [Personalized Law: Different Rules for Different People](https://www.amazon.com/Personalized-Law-Different-Rules-People/dp/0197522815)

And then we have precision (personalized?) medicine.

- [Ethical, legal, and social implications of genetic risk prediction for multifactorial disease: a narrative review identifying concerns about interpretation and use of polygenic scores](https://pmc.ncbi.nlm.nih.gov/articles/PMC10576696/)

- (RWL) Book [The Age of Scientific Wellness: Why the Future of Medicine Is Personalized, Predictive, Data-Rich, and in Your Hands](https://www.amazon.com/Age-Scientific-Wellness-Personalized-Predictive/dp/0674245946)

- [The roots of (in)equity in precision medicine: gaps in the discourse](https://pmc.ncbi.nlm.nih.gov/articles/PMC10784620/)

# Feb 8, 2025

I am back!

# Nations and International Law

Interesting article about why nations do/should obey international law. Seems opuzzling. If law is binding by some state authority, then no state authority issues internatinal law. Might be a good addition or topic for the next version of my philosophy of law class. 

- (RWL )[Why Do Nations Obey International Law?](https://openyls.law.yale.edu/bitstream/handle/20.500.13051/1394/Why_Do_the_Nations.pdf)

