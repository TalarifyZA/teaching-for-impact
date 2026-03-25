> **How to use this template**
>
> This template supports practical application of the concepts in your lesson.
> Work through it step by step. Keep your answers concise and focused.
> Return to your lesson when you are done.
>
>
> **Used in**
> {% for item in page.meta.used_in %}
> - {{ item }}
> {% endfor %}
>
> **Before you start**
>
> You will typically need:
>
> - Outputs from earlier templates (if applicable)
> - Notes from your current lesson

{% set docx_name = page.file.src_path.split('/')[-1].replace('.md', '.docx') %}
<div class="download-btn-wrapper" markdown="0">
<a class="md-button download-doc-btn" href="../../downloads/{{ docx_name }}" download>
⬇ Download as .docx
</a>
</div>
