
# Introduction
- This agent-trading farm is formed by several groups: bullish, bearish, manager and trader. 
- The idea of forking Tauric Research's trading agent repo, was to try the project fully locally, avoiding any costs.

# Setup
- Install ollama
- Pull ollama's image of LLaMa3.1, LLaMa3.2, and Qwen3. 
- Serve ollama (will start listening on port 11434 by default)
- Make sure to publish the api-keys according to the instructions in the "originalREADME.md"
  * OpenAI's api-key kan be any dummy string: the program just requires it to exist. 
  * You can pass the api-keys as shell environment constants, or as a parameter to the agents. 

# Run 
- Introduce a Ticker symbol 
- Introduce a date 
- Introduce a the type/s of research to be conducted. 
- Introduce the model's you would like to use 
  * For this step, I found optimal to use LLaMa3.2 as a lightweight-thinking model, and Qwen as the more deep-thinker one.
- RUN 

# Next steps: 
- Make docker work again. 
- Introduce concurrency in the dialogue with the agents
- Serve it on a client
- Add voice to the agents
- Add support for an array of tickers. 

