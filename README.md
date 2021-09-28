# Car-Make-Model
Task: <br />
Given two car images, the developed system must check if they have the same make and model <br />
§ Binaryoutput (1=samemake-model, 0=differentmake or differentmodel) <br />
 Difficulties:<br />
 § Carswith the samemake-model may have different colors <br />
 § Different lighting conditions 
 § Car photographs taken from different positions (e.g. front, side…)
 Verification:
Same make model: output=1
Different make model: output=0
Dataset:
40106 labeled pairs of images 
• 50% positive and 50% negative § 200x150 color images 
MAKES: 
['acura', 'audi', 'bmw', 'cadillac', 'chevrolet', 'chrysler', 'ford', 'honda', 'hyundai', 'infiniti', 'jeep', 'nissan', 'toyota', 'volkswagen']
Architecture Used:
Siamese Neural Network Architecture
