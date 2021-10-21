---
documentclass: "elsarticle"
Thesis_FP: TRUE
space: 0.9cm
Entry1: "An Exploration of Human Rationality with Empirical Evidence"
Entry2: "\\textbf{Cassandra Pengelly}"
Entry3: "\\textbf{20346212}"
Uni_Logo: img/statue.png 
Logo_width: 0.4 
Entry4: "Philosophy and Economics 871"
Entry5: "22 October 2021"
Entry6: "Word Count: 2980"
BottomRFooter: "\\footnotesize Page \\thepage" 
addtoprule: TRUE
addfootrule: TRUE           
margin: 2.3 # Sides
bottom: 2 # bottom
top: 2.5 # Top
HardSet_layout: TRUE 
bibliography: Tex/ref.bib       
csl: Tex/harvard-stellenbosch-university.csl 
RemovePreprintSubmittedTo: TRUE
toc: TRUE                       # Add a table of contents
numbersections: TRUE             # Should sections (and thus figures and tables) be numbered?
fontsize: 11pt                  # Set fontsize
linestretch: 1.2                # Set distance between lines.
link-citations: TRUE            # This creates dynamic links to the papers in reference list.
output:
  pdf_document:
    keep_tex: TRUE
    template: Tex/TexDefault.txt
    fig_width: 3.5 # Adjust default figure sizes. This can also be done in the chunks of the text.
    fig_height: 3.5
# abstract: |
  # Abstract to be written here. The abstract should not be too long and should provide the reader with a good understanding what you are writing about. Academic papers are not like novels where you keep the reader in suspense. To be effective in getting others to read your paper, be as open and concise about your findings here as possible. Ideally, upon reading your abstract, the reader should feel he / she must read your paper in entirety.
---


<!-- ############################## -->
<!-- # Start Writing here: -->
<!-- ############################## -->
\newpage

# Introduction \label{Introduction} 


Are Humans Rational? • Yes – Anderson, Chater • No – Tversky, Kahneman, (Voltaire) • They do pretty well with limited resources – Simon, Gigerenzer

When describing what it means to be human, famous Greek philosopher Aristotle defined human beings as rational animals. In fact, Aristotle emphasised that it is _rationality_ that makes humans unique and distinct from animals [@aristotle]. But exactly what it means for people to be rational has long been an interdisciplinary debate, drawing arguments from fields including philosophy, economics, psychology and mathematics. Nobel prizes

This essay^[This essay was written in R using the package Texevier by @Texevier and the write up can be found on Github [here](https://github.com/cass-code/Phil_essay).] explores what it means to be rational and whether humans fit some definition of rationality. This essay is organised as follows. Section \ref{def} presents five different criteria for defining rationality. Section \ref{rev} briefly compares different views on human rationality in the literature. Section \ref{case} presents three case studies that provide empirical evidence on rational decision-making. And the final section (\ref{con}) concludes. 

# Defining Rationality  \label{def} 

In order to understand if humans are rational, we first have to build a framework to define what we mean by rationality. Definitions of rationality relate to Max Weber's principle of methodological individualism^[The methodological precept that social phenomena should be explained as the result of individual actions [@weber], since theories of rational actions underlie theories of rationality. It follows then that theories of rationality are classically linked to the primacy of "the action frame of reference" [@parsons p.43-51; @types p.517]. While the social sciences have defined rationality in a number of different ways, this section focuses on five of the most general notions of rationality.

The first notion regards an individual as rational if she acts in a way that is intentional. This stems from Weber's sociology, where the intention of the act is primary, and the outcome of the action is of secondary importance [@fry p.26]. A simple example of a rational act under this framework would be for a person to eat ice-cream because she enjoys eating ice-cream, or alternatively, not to eat ice-cream because she wants to reduce her sugar intake. To act irrationally according to this theory would be to pursue an action based on non-intentional causes [@types p.518]. For instance, a lecturer intends to grade all his students' tests fairly, but he tends to give higher marks to papers he grades after he's eaten lunch^[The lecturer's hunger may lead him to mark more strictly]. In this case the lecturer is unaware of the influence of external factors on his deliberate decision. Thus, intentional motives are not fully governing the individual choice. It may also be that a person acts in opposition to her intentions, such as eating ice-cream because she craves sugar even though she would prefer not to eat ice-cream. While intentionality is not a particularly strong criteria by which to judge rationality, it is a useful starting point.

A second criterion for rationality is that choices should be transitive. As posited by @sen [p.323], neoclassical economics defines a rational person as one who is internally consistent in how he orders his subjective preferences. For example, if a person prefers ice-cream to chocolate, and he prefers chocolate to apples, it must follow that he prefers ice-cream to apples. There is no restriction or structure placed on the decision itself -- there is no "correct" decision. However, if a person made inconsistent decisions, he would be considered irrational. For example, a person choosing to eat apples when there is ice-cream available, given that he prefers ice-cream to apples. As shown by @math [p.147], transitivity can be written in mathematical terms as: 

\begin{align*}
Let A be a set and R be a relation on A \newline
R is transitive iff for all x, y, and z} %in% A, if xRy and yRz, then xRz.\newline
For the ice-cream example above, whenever x > y and y > z, then also x > z
\end{align*} ^[Where $x=$ice-cream, $y$=chocolate and $z$=apples]


This approach of definitional egoism sometimes goes under the name of rational choice, and it involves nothing other than internal consistency. A person's choices are considered "rational" in this ap- proach if and only if these choices can all be explained in terms of some preference relation consistent with the revealed preference defi- nition, that is, if all his choices can be explained as the choosing of "most preferred" alternatives with respect to a postulated preference relation.'2 The rationale of this approach seems to be based on the idea that the only way of understanding a person's real preference is to examine his actual choices, and there is no choice-independent way of understanding someone's attitude towards alternative



The second notion of rationality is linked to the ideal norm of consistency
or transitivity of choices. The rationality does not stem from the contents of
individual choices as such, but just from the fact that individuals are consistent
in the ordering of their subjective preferences. Preferences are clearly not
considered to be rational in this case. It is the official position of neo-classical
economics, where rationality does not involve any kind of “right” decision,
but only the fact that people do not take inconsistent decisions (Sen, 1977).
Irrationality here would correspond to inconsistent choices of the kind, again,
described by Kahneman and Tversky (2000), or Elster (2010). Here again,






The first one is to consider that individuals are rational whenever they act
in an intentional way. The intentional decision to act corresponds to the reason
someone has to act, for instance smoking for her pleasure, or not smoking in
order to avoid health problems. This classical idea can be found in Weber.

An irrational behaviour would be then to act on the basis of non-intentional
causes. For instance, Kahneman (2011) reports a study about parole
judges observed in their decisions. In this example, individual judges tend to
be more severe when they are hungrier: clearly in this case non-intentional
and unconscious causes affect intentional decisions. The judges are not aware
of the influence of those factors on their deliberate decisions. This means that
intentional motives do not have the sole influence on individual decisions;
however, in this example it is still intentional decisions that are at stake, partly
determined by unconscious trends. It can be also the case that people will act
in a manner that is opposed to their intentions, for instance when they smoke
although they would prefer not to smoke.
Intentional action can clearly be linked


All of them can be related, more or less clearly, to Popper’s “problem-solving”
notion (Popper, 1967).


## Rational Choice Theory 

## Bounded Rationality

 Neoclassical economics assumes that people are perfectly rational, whereas behavioural economics uses psychology and economic theory to create more realistic models of human decision-making [@rabin]. People are subject to certain biases and often make use of heuristics in their decision-making process, which can lead to predictable errors in judgment [@khan, @fast, @prospect]. Behavioural economics literature investigates how these biases can be combated to improve welfare outcomes. @nudge introduced the idea of a nudge^[Nudge: an intervention that alters behaviour towards a desired action. In order for an intervention to qualify as a nudge, it should be cheap and easy to avoid [@nudge].] as a way to guide people to make better choices. For example, changing the default option for organ donation to be opt-in as opposed to explicit consent could benefit potential donors (who were deterred by the registration process) and save more lives [@nudge p.176].


The concepts of loss aversion, reference dependence and regret avoidance can also be included in health interventions through a "regret lottery". @prospect describe loss aversion as a cognitive bias whereby people experience losses as more painful than the pleasure they receive from an equivalent gain. Thus, people are more willing to take on risk to avoid a loss, and are less risk-seeking when pursuing gain [@prospect p.268]. Reference dependence follows on from loss aversion and suggests that people define gains and losses relative to a reference point [@ref p.1039]. People are also subject to regret avoidance, where there is a significant emotional cost attached to regret and people make decisions to avoid regretting alternative decisions in the future [@regret]. 



# The Great Debate \label{rev}

# Case Studies \label{case} 









# Conclusion \label{con}
One of the benefits of exploring human rationality is the insight we gain into human behaviour and decision-making. Getting a clearer .
The behavioural literature and empirical studies show that lotteries can be an effective method to incentivise vaccine take-up, and South Africans appear to be well-primed for such a health intervention. This field experiment is designed to test this hypothesis.


\newpage

# References {-}

<div id="refs"></div>





