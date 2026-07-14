Machine Learning Research Engineer @ WindBorne - Application Challenge

1. Rank the open ML Research Engineer roles you're interested in (most to least):
General, Model Evaluation, Applied Research

Answer:
General > Applied Research > Model Evaluation


2. Describe an ML idea you were initially excited about but later decided was wrong or unimportant. What changed your mind?

Answer:
I initially believed sparse 3D voxels could replace dense pixel correspondences for efficient visual SLAM. After several iterations improving the feature extractor, I realized the real issue was the voxel representation itself. Voxelization introduces inherent quantization errors that discard geometric information, limiting tracking performance. I concluded that the representation, not the model, was the fundamental limitation.


3. Describe a time when you embarked on a sidequest / took initiative outside your core job responsibilities. What value did you add to your organization? What drove you to action?

Answer:
As an RA, I was tasked with comparing company descriptions using a predefined LLM prompt. Confident it would produce unreliable results, I initiated a meeting with collaborators, proposed a redesigned prompt, and developed a rigorous 10-point evaluation rubric with Likert scoring. The revised approach aligned with collaborator expectations and contributed to a conference submission.


4. How could better accuracy fail to translate into more useful forecasts for a weather model?

Answer:
A prediction system can achieve higher average accuracy while still missing rare events. For example, a model may correctly predict that temperature will remain around 28°C throughout the day but fail to forecast a brief afternoon thunderstorm. Although this model has good overall accuracy, the forecast is less useful than one that warns people about the downpour, allowing them to plan outdoor activities accordingly.


5. Describe a time you changed how you use LLMs in your work — switching models, tools, or workflows. What did you observe that prompted the change?

Answer:
I initially relied on prompt engineering to improve a vision LLM, but analyzing failure cases showed the model lacked grounded visual supervision, not better prompts. I shifted to building an automated pipeline that generated 10K+ annotated training examples and fine-tuned the model instead, leading to substantially larger performance gains than prompt optimization alone.


6. Your fav ML Twitter account?

Answer:
Andrej Karpathy (@karpathy) and François Chollet (@fchollet)