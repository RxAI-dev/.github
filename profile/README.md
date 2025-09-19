# Reactive AI
We are working on our own ideas of Reactive Neural Networks (RxNN) and Event-Driven AI, advancing from language models to AGI awareness models.

[Visit ReactiveAI's HuggingFace profile](https://huggingface.co/ReactiveAI)

## Reactive Neural Networks and Event-Driven AI
Reactive Neural Networks (RxNN) are memory-augmented neural networks with higher levels of recurrence (inter-sequence vs. intra-sequence in RNNs),
focused on processing single interactions with access to previous interactions via memory layers. We call this _**event-driven real-time processing**_
to distinguish it from classical _data-driven processing_ of the full conversation history in each interaction. This difference is crucial in case
of AGI and awareness - the key feature of humans awareness, is that we remember what we were doing 10 mins ago, without recalling the whole-day history - we
are working in real-time - just like event-driven _Reactive Neural Networks_.

In Event-Driven AI models are processing the data in reaction to environment or internal events, and are emitting other response events as a result.
Processing of input and output events by the model is called the interaction. Event or an interaction could occur in any point in continous time. Models
have to be stateful and remember the data between the interactions.

_**Strong Reactive Neural Networks**_ like **Reactor** could emit and listen to its internal events, while the _**Weak Reactive Neural Networks**_ are
working only on environment events.

## Reactor AGI

Our primary architecture - **Reactor** - is planned as the first _**awareness AGI model**_, that's modelling awareness as an _Infinite Chain-of-Thoughts_,
connected to _Short-Term and Long-Term Memory_ (_Attention-based Memory System_) and _Receptors/Effectors_ systems for real-time reactive processing.
It will be able to constantly and autonomously learn from interactions in _Continouos Live Learning_ process.

## Reactive Language Models (RxLM)
While the **Reactor** is the main goal, it's extremely hard to achieve, as it's definitely the most advanced neural network ensemble ever.

That's why we designed simplified architectures, for incremental transformation from language/reasoning models to awareness model:
- **Reactive Transformer** is introducing _Attention-based Memory System_ and adding _Short-Term Memory_ to Transformer language models
- **Preactor** is adding _Long-Term Memory_ and ability to learn from interactions

## RxNN Platform

We are working on complete Reactive Neural Networks development framework

## Additional Research
- **Sparse Query Attention** - the most cost-effective GQA variant, reducing training time/cost by ~3-10% with similar performance. Research in progress
