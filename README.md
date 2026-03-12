# go-adk-agent
go mod init my_agent/main
go mod tidy

go run agent.go

model in tutorial is rate limited on free tier with zero requests.
test Gemini 2.5 Flash, has 5 RPM.
https://aistudio.google.com/app/rate-limit

User -> hello
Agent -> Hello! How can I help you today?
User -> what is the time in san diego
Agent -> The current time in San Diego, California, United States is 03:23 PM on Thursday, March 12, 2026. San Diego is in the America/Los_Angeles timezone, which is currently Pacific Daylight Time (PDT) with a UTC offset of -7:00.


