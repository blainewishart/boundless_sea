## The goal of these examples think about different approaches to experiments.
Here I used the Playground. That won't scale to interesting experiments, but the sample code indicates that combinations of a few models, ~100 prompts, several different values for both toen limit and temperature should be easy. I don't know if it is affordable.

If it is not affordable, something very close to this should be affordable with several models and even more affordable on Colab, HF, Lambda cloud. I suspect the big question will be does Cohere provide enough extra power to justify the Cohere cost. For example, if it is really good a zero shot summaries and no human intervention is required for many docs, it may be cost effective.

It does not address the deeper issue of knowing all that the hf and/or Fastai courses offer, but I cannot do that in the short-term and I hope I can initiate conversations sooner than that. 

## Example commands (prompts) in Cohere's Playground

[Cohere Playground](https://docs.cohere.com/reference/generate)

I ran 6 example prompts. Some were quite good. One (#5), I believe, was seriously wrong. #6 had a better response to the same topic. At least it was more in line with my current beliefs.
I'm not sure what the costs of Cohere are. All this was free.At the very least, it is valuable for me to get an intuition about the effects of some common parameters mixed with different text and models. Too soon to see if that is affordable, but it does suggest a path for refactoring the boundless_sea/notebooks/Minimal_T5_for_text_summarization.ipynb experiment.

These examples are from Cohere's blog post support, not summarization. I don't think the basic structure changes. FWIW India has the world's best thorium deposits.

The playground makes it easy to look at code in Node, Python, Shell, or Curl.

### 1 Write a blog outline for a blog titled "How small, modular nuclear reactors could accelerate electrification of heavy industry"


I. Introduction

Have you ever wondered why some heavy industries still rely on fossil fuels for energy?

A. It's because they need a lot of energy.

B. And they need it to be reliable.

C. Fossil fuels are reliable.

D. And they're cheap.

E. But they're also dirty.

F. There's a better way.

G. It's called small, modular nuclear reactors.

H. They're reliable.

I. And they're clean.

J. But they're also expensive.

K. So why aren't more heavy industries using them?

L. Because the current nuclear reactor design is too large for most heavy industries.

M. And it's too expensive.

N. But there's a new design that could change all of that.

O. It's called the small, modular reactor.

P. And it's perfect for heavy industries.

Q. It's small enough to fit in a heavy industry's facility.

R. And it's modular, so it can be scaled up or down depending on the industry's needs.

S. It's also cheaper to build and operate than a traditional nuclear reactor.

T. So what are you waiting for?

### 2 write a blog outline for a blog titled "What are the downsides and risks of using small, modular nuclear reactors to accelerate electrification of heavy industry"

1. Introduction: What are small, modular nuclear reactors?

2. The benefits of small, modular nuclear reactors for heavy industry electrification

3. The risks and downsides of using small, modular nuclear reactors for heavy industry electrification

4. Conclusion: What does the future hold for small, modular nuclear reactors?

### 3 Write a section in a blog that answers the question: "What does the future hold for small, modular nuclear reactors?"
The U.S. Department of Energy (DOE) is supporting the development of small, modular nuclear reactors (SMRs) as a part of the Administration's strategy to address climate change and promote clean energy sources. SMRs are nuclear reactors that are smaller than traditional reactors, can produce between 10 and 300 megawatts of electricity (MWe), and are manufactured in a factory before being transported to a site where they would generate electricity.

DOE has undertaken several activities to support the development of SMRs, including providing funding to companies through its Gateway for Accelerated Innovation in Nuclear (GAIN) program and the Advanced Reactor Demonstration Program (ARDP), which was recently authorized by the Energy and Water Development and Related Agencies Appropriations Act, 2022. DOE is also supporting the development of a licensing framework for advanced reactors, including SMRs, through the Nuclear Regulatory Commission (NRC) and engaging with stakeholders through the Gateway for SMRs initiative. In addition, DOE has completed a cost-benefit analysis of carbon-free energy sources, including SMRs, and is working with industry to develop a domestic supply chain for advanced reactor components.

DOE is also working with industry to develop advanced fuels, including high-assay low-enriched uranium (HALEU) fuels, which are needed to power advanced reactors, including SMRs. HALEU fuels are enriched to levels above the typical 3-5% uranium-235 that is used in most nuclear reactors and can be used to improve the performance and safety of advanced reactors. DOE is supporting the development of HALEU fuels through its funding programs and through the development of a domestic HALEU production facility.

In addition to these activities, DOE is also supporting the development of advanced reactor concepts through its research and development programs. For example, the Office of Nuclear Energy is supporting the development of a molten salt reactor, which could be used to power a desalination plant, through its Advanced Reactor Demonstration Program. This program is also supporting the development of a micro-reactor that could be used for remote power, space power, and other applications.

Overall, DOE is supporting the development of SMRs as a potential clean energy source that could help address climate change and promote U.S. energy independence. The development of SMRs could also create new economic opportunities and jobs in the nuclear energy sector. However, the development and deployment of SMRs will require significant investments and regulatory approvals, and it will take some time for SMRs to be commercially available.

### 4 Considering the world as a whole, write a blog entry that discusses alternative fuels and designs for SMRs.
Alternative Fuels and SMRs

Alternative fuels are any materials or substances that can be used instead of traditional fuels to power vehicles, generators, or other machinery. Some alternative fuels are already in use, such as natural gas, propane, and hydrogen. Others are being developed, such as biofuels and solar power.

One potential use for alternative fuels is in small modular reactors (SMRs). These are nuclear reactors that are smaller than traditional reactors and can be mass-produced in a factory. They are designed to be safer and more efficient than traditional reactors, and they can be used to generate electricity or to provide heat for industrial processes.

One potential use for alternative fuels in SMRs is to power the reactor itself. Some SMRs use a molten salt as a coolant, and this salt can be heated by a variety of fuels, including solar energy, natural gas, and biofuels. This allows the reactor to be powered by a variety of different fuels, depending on what is available and what is most cost-effective.

Another potential use for alternative fuels in SMRs is to provide power for the auxiliary systems that are needed to operate the reactor. These systems include pumps, valves, and control systems, and they are needed to ensure that the reactor operates safely and efficiently. Some SMRs use fuel cells to provide power for these systems, and these fuel cells can be powered by hydrogen, natural gas, or other fuels.

Overall, alternative fuels have the potential to play a significant role in the development and deployment of SMRs. They can be used to power the reactor itself, as well as the auxiliary systems that are needed to operate it. This can help to reduce the cost of operating the reactor and to increase its flexibility and reliability.

### 5 Considering the world as a whole, write a blog entry that discusses alternatives to uranium as  fuel for SMRs. If they are relevant, please list alternative reactor designs. Please consider access to fuel over the next 50 years. 


There are a number of reasons why thorium is not a good alternative to uranium. Thorium is not fissile, so it must be converted to a fissile isotope, either U-233 or U-235. The two most common ways to do this are by irradiating thorium in a reactor or by transmuting it with a particle accelerator. In either case, the end product is the same: U-233.

Uranium is the most common naturally occurring fissile material on Earth. It can be mined and used without further processing. Thorium, on the other hand, must be converted to U-233 before it can be used as a fuel. This conversion process requires a nuclear reactor or a particle accelerator.

Uranium is found in many parts of the world, but thorium is only found in a few places. This makes uranium more widely available than thorium.

Uranium is also more abundant than thorium. There are an estimated 4.5 billion tons of uranium in the Earth's crust, compared to about 1.5 billion tons of thorium.

Uranium is also more energy-dense than thorium. One ton of uranium contains about 20 million times more energy than one ton of thorium.

Finally, uranium is easier to handle and store than thorium. Uranium is a solid at room temperature, while thorium is a liquid. This makes uranium easier to transport and store.

U. Electrify your heavy industry with small, modular nuclear reactors.

### 6 Considering the problems with Thorium as a fuel for SMRs, what are some reasons China is investing in thorium-powered molten-salt reactors?
China is investing in thorium-powered molten-salt reactors because they offer a number of potential advantages over traditional nuclear reactors, including improved safety, increased proliferation resistance, and the ability to utilize more abundant fuel resources.

One of the main advantages of thorium-powered molten-salt reactors is that they are capable of utilizing thorium as a fuel source. Thorium is more abundant than uranium and can be found in many countries around the world. It is also more difficult to weaponize than uranium, making it a more proliferation-resistant fuel source.

In addition to these advantages, thorium-powered molten-salt reactors have the potential to be safer and more efficient than traditional nuclear reactors. They operate at lower temperatures, which can reduce the risk of accidents and make them more resilient to natural disasters. They also have the potential to be more efficient in converting fuel into energy, which could reduce the amount of nuclear waste produced.

Overall, China is investing in thorium-powered molten-salt reactors because they offer a number of potential advantages over traditional nuclear reactors, including improved safety, increased proliferation resistance, and the ability to utilize more abundant fuel resources.