# music for emotional expression
## summary
Summarize the findings of the three most important papers in the [[queries#variant for self expression|mt* query]] results

### self expression in music
This finding comes from the first paper which seeks to evaluate the connections that children make with different music qualities.

| musical parameter | associations |
| :-- | :-- |
| tempo | associated with intensity |
| volume |  associated with intensity |
| pitch | associated with intensity |
| articulation | associated with intensity |
| timbre | associated with intensity |
| noise | associated with intensity and negative emotion |
| modality | major/minor associated with happy/sad |

Interestingly, most parameters deal with intensity of emotions.


| parameter  | happy | sad | anger |
| :-- | :-- | :-- | :-- |
| tempo | fast | slow | fast |
| volume |  med-high | low | high |
| pitch | high | low | high |
| articulation | staccato | legato | staccato |
| timbre | bright | dull | sharp |
| noise | none | none | high|
| modality | major | minor | minor |

Note how if we map our emotions on a 2D grid with x being polarity and y being intensity we can see why intense emotions like anger and happiness share many aspects.

**although modality is a strong indicator of polarity, its a western feature**

### minimally verbal self expression modalities
This finding comes from our second paper on identifying expressive modalities of minimally verbal autistic children for the participatory design process

Each modality contains two types, auto-expressive and socio-expressive. This is a descriptor of whether the communication is prompted by internal desires or social desires.

| Modality | Auto-expressive | socio-expressive |
| :--: | :-- | :-- |
| words | conveying interest | describing actions |
| sounds | self-soothing | attention-seeking |
|  bodily movement | dancing | interacting with peers |
| touch/gesture | stroking objects | pointing to object |
| play | independent play | independently initiated turn taking play with peers |
| creativity | making up a song | collaborative drawing |

The paper proposes that by including these modalities as means of expression we can create a more accessible product.


#### note about age ranges
Children at 3 can distinguish happy and sad
Children at 4-6 can distinguish anger and fear although they mix these last two up

### sensebox prototype
The third paper discussed making a prototype for sound and music play back.
Mentions a simple python set up for playing back audio and altering but no links to be found :(




## full paper reviews

### expression of emotion through musical parameters in 3- and 5-year-olds.
#### manipulation parameters
- tempo
- volume 
- pitch
- articulation
- timbre
- noise


#### emotional associations
Juslin and Timmers \[22\] show that ...

##### happiness
- fast tempo
- major mode
- medium-high or high sound level
- high pitch
- staccato articulation
- bright timbre
##### sadness
- slow tempo
- minor mode
- low sound level
- low pitch
- legato articulation
- dull timbre
##### anger
- fast tempo
- high sound level
- high pitch
- staccato articulation
- sharp timbre
- spectral noise


3–5-year olds give highly similar responses to adults when asked to match musical pieces to facial expressions reflective of basic emotions _(happy, sad, angry, fear and neutral_)

Happiness and sadness are easiest to percieve and this precedes other emotions.
3 year olds distinguish happy and sad music while 4-6 year olds can percieve and identify happiness, sadness, anger, and fear. Note children often confuse fear and anger and sometimes confuse angry and happy

Tempo is a universal marker of excitment/arousal. Major and minor distinction is particularly western european.

Dalla Bella et al. ([[https://web-p-ebscohost-com.ezproxy.library.wwu.edu/ehost/detail/detail?vid=0&sid=b6c87988-e548-49f1-9336-92e5f139a483%40redis&bdata=JnNpdGU9ZWhvc3QtbGl2ZQ%3d%3d#bib7 "7" | 7]]) modified both tempo and mode of pre-existing classical music pieces, and reported that 3–4-year-olds failed to distinguish happy and sad expression, 5-year-olds' responses were affected by tempo change only, and 6–8-year-olds and adults were affected by both mode and tempo manipulations

Similarly, Gregory, Worrall, and Sarge ([16]) showed that 7–8 year-olds but not 3–4-year-olds were able to distinguish between sad and happy expression when only mode of the excerpts was modified

tempo and loudness in particular
Webster and Weir ([42]) showed that the typical positive association between tempo and happiness was inverted among minor, nonharmonised phrases

### self expression by design: co-designing the expressiball with minimally-verbal children on the autism spectrum
Worked with **20 minimally verbal autistic children aged 4-8**
Developed 6 new modalities for self-expression. 
Each modality can occur across two dimensions
Prototype relies on the idea that children on the spectrum often seek **sensorimotor feedback**

#### modalities of expression
| Modality | Auto-expressive | socio-expressive |
| :--: | :-- | :-- |
| words | conveying interest ("gloves") | describing actions ("bounce") |
| sounds | self-soothing (low humming) | attention-seeking ("uh uh!") |
|  bodily movement | dancing with a ball | throwing the ball to a peer |
| touch/gesture | stroking the ball | pointing to the ball |
| play | throwing ball up for peripheral vision stimulatiion | independently initiated turn taking games |
| creativity | making up a song in the ball | collaborativer drawing on the ball |

##### We propose that,  
by designing in opportunities for self-expression to the  
design process itself, the resultant designs are inherently  
capable of supporting self-expression across multiple  
modalities. We call this Self-Expression by Design

other tangible user interfaces (tuis) for support in autism  
include; storytelling through augmented paper [1], sonic  
tuis for social collaboration [43], interactive surfaces for  
e.g. music therapy for sensorimotor challenges [10] or free  
play [46], smart textiles [71], and musical TUIs [63]. While  
the aforementioned work is stimulating, we highlight that, as  
yet, very few studies focus on 1) self-expression and 2)  
minimally-verbal contexts.

#### conclusion  
Minimally-verbal children’s inclusion and participation is often limited in co-design, as many practices focus on verbal collaboration.

We investigated how minimally-verbal  children on the autism spectrum express themselves, in order to understand how to better include them in co-design. We found that children are continually self-expressing through modalities of....
- Words
- Sounds
- Bodily Movements
- Touch and Gesture
- Creativity
- Play. 
 
We propose these six modalities of auto- and socio-expression, as a means of  
tuning into and identifying how a child self-expresses. We contributed a design case study of the ExpressiBall, a playful tangible ball technology, arguing that multimodal forms of  technology are needed to support self-expression for this group.

Self-expression can be fluid, changing, and highly individualised. 
By learning to identify and support different modalities of self-expression, the researcher or designer can equip themselves with the ability to understand design contributions beyond the verbal, while also supporting agency and choice in participatory contexts.

### sensebox: a diy prototyping platform to create audio interfaces for therapy

a small device that comes with an audio play back module in a 3d printed case (raspi) and rfid tags to embed in physical objects.
Musical instruments are too dificult

#### usage scenario 1
the audio playback module can be placed on a table or similar surface (e.g., a wheelchair tray). If more stability is needed, it can be fastened to the surface using Velcro or glue strips.  

When tagged objects are brought to the proximity of the sensor, a corresponding audio file is played back. Since in this scenario the audio playback module remains stationary  
and tagged objects are brought to its proximity, it is best suited to using small tagged objects and for users who would have difficulty with grasping and holding the audio  
module. 

The objects can then be used in different speech language therapy exercises, for example when therapists want to teach the name of objects to clients or encourage  
them to communicate using objects that symbolize activities or greetings. 

**For music therapy exercises,** musical sounds can be activated when a client brings an object close to the module.  

#### usage scenario 2
tags can be attached to potentially larger objects (e.1g., tables, chairs, ...) and a user  
can hold the audio playback module with their hands and move it close to the objects to trigger the playback of corresponding audio sounds. An example of this usage in  
the context of therapy is when a client with visual impairments is encouraged to explore a space or environment and scan tags in a room using SenseBox.

#### needs
- **customizabilty**
- **affordability**
- **accessibility**


## personal thoughts
- high overtone content leads to harsh/negative sounds
- timbres focusing on r0 and r1 sound "pure" and are peaceful

X axis = polarity
Y axis = intensity

![[emotioncolorwheel.png]]