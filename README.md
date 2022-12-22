# Speech-privacy-preservation-based-on-apparent-attribute-transformation

Speech signals contain private information about the speaker including health, gender, age, and mood,
making it essential to protect speech data from abuses of personal privacy. Existing approaches to
secure speech achieve some protective effect, but are somewhat reversible and therefore insufficient.
Additionally, protecting speech privacy often hurts the intelligibility of the speech and prevents its use
by automatic speech recognition systems found in cars and mobile devices. To address these issues, we
divide the two essential parts of the task into speech privacy via feature replacement and, secondarily,
speech intelligibility for ASR. We implement a method to obscure the original speech and, then, by
training the mutual information between the two tasks, we generate noise [1] that is supplementary to
the speech content. After adding this noise to the synthesized speech following feature replacement,
the speech can be used by ASR systems. In our tests, the WER of speech content recognition improved
to 12.64% without our method, with a needed decline in the recognition accuracy of apparent attributes
(gender, age) to 49.62% and 40.68% for gender alone and age alone, respectively, and to 36.54% for
the two combi

