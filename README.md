MedIR2014-RelanceAssessment
===========================

Material related to B.Koopman, G.Zuccon. Why Assessing Relevance in Medical IR is Demanding. 

The following files are included:

## http-interaction.log

The HTTP interaction log from Django webserver. POSTs represent the assessor judging the given query and document

## query-difficulty_quality_comment.txt

Tab separated file with the following fields:

`queryId	queryText	difficulty	quality	comment`

where

difficulty: 0=easy, 1=moderage, 2=hard and quality: 0=poor, 1=moderate, 3=high

## trec_medtrack_additional_qrels.txt

The new qrels for additional documents judged. Supplied in the standard TREC qrel format.