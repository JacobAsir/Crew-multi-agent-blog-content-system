# Crew-multi-agent-blog-content-system

Using CrewAI, I developed a 𝗺𝘂𝗹𝘁𝗶-𝗮𝗴𝗲𝗻𝘁 𝘀𝘆𝘀𝘁𝗲𝗺 to automate blog content creation from YouTube videos. The system features two specialized agents working together: a Blog Researcher and a Blog Writer.

𝗛𝗼𝘄 𝗜𝘁 𝗪𝗼𝗿𝗸𝘀

𝗕𝗹𝗼𝗴 𝗥𝗲𝘀𝗲𝗮𝗿𝗰𝗵𝗲𝗿 𝗔𝗴𝗲𝗻𝘁:
𝗚𝗼𝗮𝗹: Extract relevant video content from YouTube based on a given topic.
𝗖𝗮𝗽𝗮𝗯𝗶𝗹𝗶𝘁𝗶𝗲𝘀: Uses the YoutubeChannelSearchTool to search a specific channel. Analyzes and summarizes video content.
𝗢𝘂𝘁𝗽𝘂𝘁: A detailed, three-paragraph report on the topic.

𝗕𝗹𝗼𝗴 𝗪𝗿𝗶𝘁𝗲𝗿 𝗔𝗴𝗲𝗻𝘁:
𝗚𝗼𝗮𝗹: Transform the research into a compelling blog post.
𝗖𝗮𝗽𝗮𝗯𝗶𝗹𝗶𝘁𝗶𝗲𝘀: Summarizes the research output into engaging and accessible content. Outputs the final blog post as a markdown file.
