 # Decentralised Physical Infrastructure Network (DePIN)

<ins>**Innovation & Ideation**</ins>

```{admonition} Key Insights
:class: tip
- DePINs enhance transparency and user control, shifting management from centralised entities to a community-based model.
- Blockchain and DLT enable secure, innovative applications like Filecoin, which democratises storage and rewards participation.
- The tokenisation model in DePIN incentivises contributions (e.g., GPU power, storage) with tokens, sustaining network operations.
- Zero-Knowledge Proofs (ZKPs) in DePIN ensure secure and private verification processes, enhancing data integrity.
- DePINs require extensive infrastructure, potentially limiting participant access and risking centralisation by powerful entities like mining pools.
- By decentralising storage and other services, DePIN could reduce costs by up to 70%, though user engagement and profitability remain critical for growth.
- Successful expansion of DePIN depends on overcoming scalability, governance, and resource access challenges to achieve broader adoption.
```

## Introduction

Decentralisation stands as a pivotal method for ensuring information transparency. The emergence of blockchain and Decentralised Ledger Technology (DLT) has illuminated the prospects of integrating such innovations into various infrastructures. Bitcoin introduced the concept of decentralisation as a peer-to-peer cash network {cite}`nakamoto2008bitcoin`. Decentralisation has been a main topic of discussion in recent trends {cite}`organisation2019making`. This concept has also been explored in the context of transitioning traditional physical networks towards decentralisation {cite}`ballandies2023taxonomy`.

Numerous infrastructures, such as wireless networks, cloud storage, and computing, can benefit from decentralisation. DePIN, for instance, can be defined as an infrastructure network constructed, maintained, and operated through blockchain protocols within a decentralised and open network {cite}`lepcha2024decentralized`.

The current solution provides a centralised infrastructure for users, such as AWS, where Amazon oversees controlling and maintaining the cloud services. Conversely, in a decentralised solution, the community and token holders assume responsibility for facilitating and delivering these services. This science note delves into the workings of this technology, its applications, and its implementation strategies. Moreover, we analyse the benefits of Decentralised Physical Infrastructure Networks (DePIN) alongside the concerns surrounding their use within physical infrastructures.

## What is DePIN and How it Works

```{figure} images/depin.drawio.png
---
width: 369.75px
height: 347.75px
name: depin_diagram
---
DePIN Life Cycle.
```

DePIN has garnered attention in recent developments for bridging decentralisation with the physical realm. Decentralisation has promised values such as enhancing transparency, reducing censorship, improving user control by granting access to the decision-making processes, and diminishing reliance on intermediaries within the network {cite}`sarkar2023generalised`.

Functioning as a crypto-economic system, DePIN comprises several components: i) individual autonomous actors, ii) economic policies embedded in software, iii) emergent properties arising from the interactions of those actors according to the rules defined by the software {cite}`ballandies2023taxonomy` {cite}`ballandies2022fundamentals`.

`````{margin} **Tokenisation**
Tokenisation is the process of converting assets or rights into digital tokens that can be recorded and managed. These tokens can represent a variety of assets or entitlements, enabling secure, transparent, and decentralised transactions within the network.
`````

At the core of DePIN's operation lies the tokenisation model, which incentivises participants to contribute essential resources to the network. This participation entails offering resources such as GPU power, hotspots, and storage. Users within the network benefit from transactions based on supply and demand dynamics, wherein they must use the provided token to access storage offered by network participants {cite}`ideasoft2023decentralized`.

`````{margin} **Zero-Knowledge Proof**
A ZKP is a cryptographic method that enables one party (the prover) to prove to another party (the verifier) that they possess a specific piece of information, without disclosing the information itself, apart from asserting its truth.
`````

Participant verification is essential in a vast network of users utilising their devices to sustain DePIN. Methods like Zero-Knowledge Proof (ZKP) enable the verification of new members while ensuring they possess the requisite equipment without revealing their credential information {cite}`sarkar2023generalised`.

## Use Cases

Filecoin stands out as a great example of DePIN utilisation, offering decentralised storage solutions. Miners can engage with the network by allocating their unused storage and earning rewards, effectively transforming cloud storage into an algorithmic market facilitated by peer-to-peer networking.

This system uses cryptographic algorithms to ensure that all files are saved securely. The community behind Filecoin governs the network’s authority. They are committed to upholding transparency, decentralisation, and open-source principles throughout the network.

Numerous advantages come from utilising Filecoin services. Being a decentralised network, there are no geographical limitations on user participation, fostering inclusivity. However, users should consider the efficiency of their equipment and electricity costs. Additionally, the transparency and security provided by cryptographic algorithms enhance user trust. Filecoin's commitment to open-source development ensures users have access to the latest software for seamless operation.

Nevertheless, alongside the benefits come certain concerns. Profitability challenges have jeopardised user interest, affecting network participation. The scarcity of users providing necessary equipment and facilities has currently impacted the network's efficacy. Enhanced profitability systems and increased user engagement could mitigate these challenges and drive network growth {cite}`filecoin2024depin` {cite}`schoeman2024filecoin`.

## Advantages

Ballandies et al. {cite}`ballandies2023taxonomy` explore the advantages of employing DePINs across various domains. Firstly, decentralisation offers resilience and reliability to networks. Blockchain's transparency feature fosters trust among users by ensuring transparency while maintaining participant anonymity. Additionally, permissionless blockchain networks enhance scalability and utility within the infrastructure network.

Cost efficiency emerges as another key benefit of DePIN networks. Adopting a decentralised approach akin to AWS may cut cloud storage costs by as much as 70%. Despite challenges in infrastructure development, this approach holds promise, particularly for smaller businesses {cite}`selkis202crypto`.

## Concerns

Decentralised Physical Infrastructure Networks are still in their infancy, with significant room for development and maturation. Despite the numerous benefits, there are downsides to the technology. Concerns about the governance and the actual decentralisation of the network persist. Even though these networks are foundational to decentralisation, they require extensive technological infrastructure, which may not be accessible to all users. For example, you may have a few gigabytes of storage on your laptop, but this will not suffice for a massive network. Mining pools often have the required infrastructure, giving them the potential to dominate network control, which can shift the decentralisation in their favour.

Additionally, these networks often necessitate large-scale resources such as powerful GPUs, which may not be accessible to many users. This limitation can affect the scalability of the network. 

## Conclusion

Although DePIN technology is on its path to revolutionising the decentralisation of physical infrastructure like sensors, storage, GPUs, and more, there are several concerns that need to be addressed. Proper implementation of these physical infrastructures can help to reduce costs, increase transparency, and enhance overall network resilience. DePINs also offer the potential to take control from centralised players like AWS, challenging them by empowering individuals to participate in the network with their equipment. As the technology develops, addressing these concerns effectively will be crucial to its success and widespread adoption. 


<div style="text-align: right;font-weight: bold;">Hamed Mousavi</div>
<div style="text-align: right;font-style: italic;">March 2024</div>

## References
 
```{bibliography}
:filter: docname in docnames
```