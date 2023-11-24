# Representing Images, Sound and Other Data

## Specification

| Content | Additional information |
| --- | --- |
| Describe how bit patterns may represent other<br>forms of data, including graphics and sound. |  |
| Understand the difference between analogue<br>and digital:<br><ul><li> data<br></li><li> signals.</li></ul> |  |
| Describe the principles of operation of:<br><ul><li> an analogue to digital converter (ADC)<br></li><li> a digital to analogue converter (DAC).</li></ul> |  |
| Know that ADCs are used with analogue<br>sensors. |  |
| Know that the most common use for a DAC is<br>to convert a digital audio signal to an analogue<br>signal. |  |
| Explain how bitmaps are represented. |  |
| Explain the following for bitmaps:<br><ul><li> resolution<br></li><li> colour depth<br></li><li> size in pixels.</li></ul> | The size of an image is also alternatively<br>sometimes described as the resolution of an<br>image.<br>Size of an image in pixels is width of image in<br>pixels x height of image in pixels.<br>Resolution is expressed as number of dots per<br>inch where a dot is a pixel.<br>Colour depth = number of bits stored for each<br>pixel. |
| Calculate storage requirements for bitmapped<br>images and be aware that bitmap image files<br>may also contain metadata. | Ignoring metadata,<br>storage requirements = size in pixels x colour<br>depth<br>where size in pixels is width in pixels x height in<br>pixels. |
| Be familiar with typical metadata. | eg width, height, colour depth. |
| Explain how vector graphics represents images<br>using lists of objects. | The properties of each geometric object/shape<br>in the vector graphic image are stored as a list. |
| Give examples of typical properties of objects. |  |
| Use vector graphic primitives to create a simple<br>vector graphic. |  |
| Compare the vector graphics approach with the<br>bitmapped graphics approach and understand<br>the advantages and disadvantages of each. |  |
| Be aware of appropriate uses of each approach. |  |
| Describe the digital representation of sound in<br>terms of:<br><ul><li> sample resolution<br></li><li> sampling rate and the Nyquist theorem.</li></ul> |  |
| Calculate sound sample sizes in bytes. |  |
| Describe the purpose of MIDI and the use of<br>event messages in MIDI. |  |
| Describe the advantages of using MIDI files for<br>representing music. |  |
| Know why images and sound files are often<br>compressed and that other files, such as text<br>files, can also be compressed. |  |
| Understand the difference between lossless<br>and lossy compression and explain the<br>advantages and disadvantages of each. |  |
| Explain the principles behind the following<br>techniques for lossless compression:<br><ul><li> run length encoding (RLE)<br></li><li> dictionary-based methods.</li></ul> |  |
| Understand what is meant by encryption and be<br>able to define it. | Students should be familiar with the terms<br>cipher, plaintext and ciphertext.<br>Caesar and Vernam ciphers are at opposite<br>extremes. One offers perfect security, the other<br>doesn’t. Between these two types are ciphers<br>that are computationally secure – see below.<br>Students will be assessed on the two types.<br>Ciphers other than Caesar may be used to<br>assess students' understanding of the principles<br>involved. These will be explained and be similar<br>in terms of computational complexity. |
| Be familiar with Caesar cipher and be able to<br>apply it to encrypt a plaintext message and<br>decrypt a ciphertext.<br>Be able to explain why it is easily cracked. |  |
| Be familiar with Vernam cipher or one-time pad<br>and be able to apply it to encrypt a plaintext<br>message and decrypt a ciphertext.<br>Explain why Vernam cipher is considered as a<br>cypher with perfect security. | Since the key k is chosen uniformly at random,<br>the ciphertext c is also distributed uniformly.<br>The key k must be used once only. The key k is<br>known as a one-time pad. |
| Compare Vernam cipher with ciphers that<br>depend on computational security. | Vernam cipher is the only one to have been<br>mathematically proved to be completely secure.<br>The worth of all other ciphers ever devised is<br>based on computational security. In theory,<br>every cryptographic algorithm except for<br>Vernam cipher can be broken, given enough<br>ciphertext and time. |
