# test-gpu-llama
basic setup to run test-gpu-llama

# A100(8units 40GB)
      Llama.generate: 14 prefix-match hit, remaining 1 prompt tokens to eval
      llama_perf_context_print:        load time =     418.18 ms
      llama_perf_context_print: prompt eval time =       0.00 ms /     1 tokens (    0.00 ms per token,      inf tokens per second)
      llama_perf_context_print:        eval time =    1821.81 ms /    59 runs   (   30.88 ms per token,    32.39 tokens per second)
      llama_perf_context_print:       total time =    2016.85 ms /    60 tokens
# L4(2 units 22.5GB ram)
      llama_perf_context_print:        load time =     413.63 ms
      llama_perf_context_print: prompt eval time =     413.40 ms /    15 tokens (   27.56 ms per token,    36.28 tokens per second)
      llama_perf_context_print:        eval time =    2987.09 ms /    42 runs   (   71.12 ms per token,    14.06 tokens per second)
      llama_perf_context_print:       total time =    3556.06 ms /    57 tokens
# T4(2 units 15GB ram)
      Resposta:
      llama_perf_context_print:        load time =     480.90 ms
      llama_perf_context_print: prompt eval time =     480.63 ms /    15 tokens (   32.04 ms per token,    31.21 tokens per second)
      llama_perf_context_print:        eval time =    7539.91 ms /    58 runs   (  130.00 ms per token,     7.69 tokens per second)
      llama_perf_context_print:       total time =    8218.08 ms /    73 tokens
