# Characterise And Understand How Twitter Is Used To Discuss Economic Topics
Abstract—In the realm of modern communication, social media
platforms have become essential spaces for discussing various
topics, including economics. This study dives into the intricate
landscape of economic discussions on Twitter, with a specific
focus on the sub-network defined by the hashtag #Econtwitter.
By understanding how this group interacts, community detection,
and shedding light on the popular themes, we aim to gain
insights into economic conversations. Using natural language
processing, text is refined by removing hashtags, links, and
non-ASCII characters. Tokenization generates word embedding
via Word2Vec for visual representation of economic discussions.
Cluster interpretation via word clouds and Latent Dirichlet
Allocation (LDA) reveals dominant themes in each community,
adding qualitative insight. Assigning topics unveils core economic
discourse themes, enriching understanding. Network analysis
using Gephi, based on retweet relationships, illustrates user
interactions visually. To meet the main objective, a comprehensive
methodology while using a dataset of tweets is used where each
tweet’s text becomes the main feature, and its community cluster
serves as the label. Employing a Support Vector Machine (SVM)
classifier, this study yields predictive insights by analyzing tweet
text to forecast clusters with an accuracy of approximately 60%.
Moreover, the insights derived from this research possess the
capacity to enlighten public discourse, steer policy deliberations,
and cultivate a more knowledgeable societal dialogue concerning
economic affairs.



I. INTRODUCTION
The fusion of social media and intellectual exchanges has
ushered in a shift in communication during a time when digital
platforms have had a great impact on sharing information and
global discussion. In this setting, the discipline of economics,
which is intricately wrapped with social structures, has discovered
a virtual forum to discuss its complexities, implications,
and debates. At the crux of this phenomenon is Twitter, a microblogging
platform that has developed into a vibrant forum
for debates on a wide range of topics, including economics.
The goal of this study is to navigate the complex landscape
of economic discourse within the Twitter ecosystem, paying
particular attention to the distinctive subnetwork shaped by the
hashtag #Econtwitter.
Understanding the underlying aspects of this discourse
is growing in significance as economic conversations move
beyond academic settings and onto digital platforms. Economic
ideas, policies, and discussions have gone beyond
the boundaries of academic literature, influencing the digital
sphere and shaping public perceptions, policy debates, and
even fiscal choices. Echoing the sentiments articulated by
David Colander, Richard P. F. Holt, and J. Barkley in their
work ”The Changing Face of Economics: Conversations with
Cutting Edge Economists,” the process of analyzing economic
conversations assumes significance as economics stands at a
crucial moment, transitioning from a steady adherence to the
traditional triad of rationality, greed, and equilibrium toward a
more multifaceted triad enclosing purposeful behavior, enlightened
self-interest, and sustainability [1]. When we consider
how economics affects policies, businesses, and individual
financial decisions, the importance of this study becomes
apparent. When economics meets the strong communication of
social media, its impact becomes even stronger. This makes
it possible for policymakers, economists, and everyone else
to engage in discussions that could influence how economies
develop. Understanding the structures behind these online economic
discussions enables us to make wiser decisions, develop
policies based on facts, and improve economic literacy.
The project is unique and original because of a number of
important factors. While other studies have investigated into
how social media plays a part in economic discussions, the
present one stands out because it is focused specifically on the
distinctive #Econtwitter dataset. This unique method involves
a thorough analysis of this specialised subnetwork, enabling
an extensive analysis catered to a particular community [2].
Notably, this project’s distinctive hallmark is the integration
of various methodologies, including network analysis, natural
language processing, machine learning, and topic modelling.
This multifaceted strategy reveals structural patterns, thematic
content, and predictive insights, allowing for an in-depth understanding
of the dynamics of the subnetwork. The inclusion
of a classifier that predicts tweet clusters adds a predictive
dimension to the research, which is a noteworthy feature. This
predictive dimension demonstrates how machine learning can
be used to understand the underlying patterns and content
associations present in economic discussions. This strategy
represents a cutting-edge methodology for extracting insights
from social media platform discourse.
