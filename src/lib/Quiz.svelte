<script>
    export let quizIndex = 0;
    const quiz = [
        {
            question: 'Is the Sky blue ?',
            correctAnswer: 0,
            answer: [
                'Yes',
                'No'
            ]
        },
        {
            question: 'Is grass purple ?',
            correctAnswer: 1,
            answer: [
                'Yes',
                'No'
            ]
        }
    ]
</script>

<div>
    {quizIndex}
</div>