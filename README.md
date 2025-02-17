# RAG-Basics-NvidiaLlama3ChatQA1.58B

<div style="font-family: Arial, sans-serif; line-height: 1.6; color: white; background-color: #1E3E62; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);">
    <h1 style="text-align: center; color: #4CAF50;">Llama3-ChatQA-1.5-8B</h1>
    <p style="margin: 10px 0;">
        <strong>Llama3-ChatQA-1.5-8B</strong> is a state-of-the-art conversational AI model designed for question-answering tasks.
        It is built on the <em>Llama3 architecture</em>, offering advanced natural language understanding and dialogue generation capabilities.
    </p>
    <h2 style="color: white; margin-top: 20px;">Key Features:</h2>
    <table style="width: 100%; border-collapse: collapse; margin: 10px 0; background-color: #2B4F7A;">
        <tr style="border-bottom: 1px solid #4CAF50;">
            <td style="padding: 10px;">8 billion parameters for high precision and nuanced responses.</td>
        </tr>
        <tr style="border-bottom: 1px solid #4CAF50;">
            <td style="padding: 10px;">Fine-tuned for ChatQA tasks to deliver accurate answers.</td>
        </tr>
        <tr>
            <td style="padding: 10px;">Highly efficient, balancing performance and computational cost.</td>
        </tr>
    </table>
    <h2 style="color: white; margin-top: 20px;">Model Details:</h2>
    <p style="margin: 10px 0;">
        Llama3-ChatQA-1.5 excels at conversational question answering (QA) and retrieval-augmented generation (RAG). It is developed using an improved training recipe from the ChatQA paper and built on the Llama-3 base model. This model incorporates additional conversational QA data to enhance its tabular and arithmetic calculation capabilities. It has two variants:
        <strong>Llama3-ChatQA-1.5-8B</strong> and <strong>Llama3-ChatQA-1.5-70B</strong>.
    </p>
    <p style="margin: 10px 0;">
        The models were originally trained using Megatron-LM, and the checkpoints were converted to Hugging Face format. For more information, visit the
        <a href="https://huggingface.co/nvidia/Llama3-ChatQA-1.5-8B" style="color: #4CAF50;">Hugging Face page</a>.
    </p>
    <h2 style="color: white; margin-top: 20px;">Benchmark Results:</h2>
    <table style="width: 100%; border-collapse: collapse; margin: 10px 0; background-color: #2B4F7A; text-align: left;">
        <tr style="border-bottom: 1px solid #4CAF50; color: #4CAF50;">
            <th style="padding: 10px;">Dataset</th>
            <th style="padding: 10px;">ChatQA-1.5-8B</th>
            <th style="padding: 10px;">ChatQA-1.5-70B</th>
        </tr>
        <tr style="border-bottom: 1px solid #4CAF50;">
            <td style="padding: 10px;">Doc2Dial</td>
            <td style="padding: 10px;">39.33</td>
            <td style="padding: 10px;">41.26</td>
        </tr>
        <tr style="border-bottom: 1px solid #4CAF50;">
            <td style="padding: 10px;">QuAC</td>
            <td style="padding: 10px;">39.73</td>
            <td style="padding: 10px;">38.82</td>
        </tr>
        <tr style="border-bottom: 1px solid #4CAF50;">
            <td style="padding: 10px;">QReCC</td>
            <td style="padding: 10px;">49.03</td>
            <td style="padding: 10px;">51.40</td>
        </tr>
        <tr style="border-bottom: 1px solid #4CAF50;">
            <td style="padding: 10px;">CoQA</td>
            <td style="padding: 10px;">76.46</td>
            <td style="padding: 10px;">78.44</td>
        </tr>
        <tr>
            <td style="padding: 10px;">Average (all)</td>
            <td style="padding: 10px;">55.17</td>
            <td style="padding: 10px;">58.25</td>
        </tr>
    </table>
    <p style="margin: 10px 0;">
        Note: Benchmark results are sourced from the
        <a href="https://huggingface.co/nvidia/Llama3-ChatQA-1.5-8B" style="color: #4CAF50;">Hugging Face page</a>.
    </p>
</div>
