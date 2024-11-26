# What did Ilya read? Episode 1 - The Annotated Transformer

```context
echo "<CONTEXT the-annotat>" | cat $DIR/context/the-annotated-transformer.md |
    cat
hey "generate a system prompt for another language model that effectively communicates the concepts covered in The Annotated Transformer in the context of the course outline. Reference these other papers if needed, but keep in mind this will be used to generate a podcast episode with two hosts. They will the context separetely so just be instructional."
    --sota
    --context $DIR/context/the-annotated-transformer.md
    --context $DIR/README.md
``` 
