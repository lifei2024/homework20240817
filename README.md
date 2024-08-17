作业：
实现 role-play 对话数据生成工具，包含下列功能：
基于一段文本（自己找一段文本）生成角色人设，可借助 ChatGLM 实现。
给定两个角色的人设，调用 CharacterGLM 交替生成他们的回复。
将生成的对话数据保存到文件中。

完成过程：
通过定义三个函数来方便实现这个功能
1.定义一个函数generate_character_profiles，使用ChatGLM系列模型中的glm-4模型生成角色人设。
2.定义一个函数create_chat_completion，通过生成的角色人设来使用CharacterGLM API生成对话回复。
3.定义一个函数save_dialogue_to_file，将两个角色的聊天记录保存到一个文件中。
