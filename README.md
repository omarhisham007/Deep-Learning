# Deep-Learning
*   **UTK Face Dataset** images have labels embedded in their name, as per the following nomenclature:
 * [age]\_[gender]\_[race]\_[time].jpg
* **Import Gender Dataset** from Drive and **read gender labels** from file name 
* Convert all images to **grayscale**
* Using **X epochs** on our **defined CNN Architecture**, comprising of:
    - an input *Conv2D* layer (with 32 filters) paired with an *MaxPooling2D* layer,
    - 3 pairs of *Conv2D* (with 64, 128 & 256 filters) and *MaxPooling2D* layers,
    - 1 *Dense* layer with 128 nodes, and
    - an output *Dense* layer with 3 nodes.
