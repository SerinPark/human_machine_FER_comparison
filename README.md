# human_machine_FER_comparison
Comparing FER of humans and machines using saliency/attention maps

This is a source code for 2021ACPR paper: Comparing Facial Expression Recognition in Humans and Machines: Using CAM, GradCAM, and Extremal Perturbation

We first obtained human attention maps during a 2AFC task of classifying facial expressions (images from AffectNet), using a custom-written experimental program.
Then we trained one-versus-one models on AffectNet dataset. 

Finally, we compared human attention maps and model saliency maps using dice coefficient.
