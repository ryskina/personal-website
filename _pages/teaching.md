---
layout: teaching
permalink: /teaching/
title: teaching & talks
description: teaching materials I created & invited talks
nav: true
---

<!-- ### Carnegie Mellon University

<div class="card class mt-3">
  <div class="p-3">
    <div class="row">
      <div class="col-sm-10">
        <h5 class="card-title"><a href="http://demo.clab.cs.cmu.edu/11711fa18/" target="_blank">Algorithms for Natural Language Processing</a></h5>
        <h6 class="card-subtitle font-italic">Fall 2018: TA & Guest Lecturer</h6>
      </div>
      <div class="col-sm-2 text-sm-right">
        <span class="badge" style="background-color:var(--global-theme-color); opacity:0.8"> 
          11-711
        </span>
      </div>
    </div>
    <ul class="card-text font-weight-light list-group list-group-flush">  
      <li class="list-group-item">
        <div class="row">
          <div class="col-sm-10">
            Recitation: Parsing Reranker
          </div>
          <div class="col-sm-2">
            <a href="http://demo.clab.cs.cmu.edu/11711fa18/recitation_notes/recitation_slides_rerank.pdf" target="_blank">slides</a>&nbsp;
          </div>
        </div>
      </li>  
    </ul>
    
  </div>
</div>


<div class="card class mt-3">
  <div class="p-3">
    <div class="row">
      <div class="col-sm-10">
        <h5 class="card-title"><a href="http://www.cs.cmu.edu/afs/cs/user/tbergkir/www/11711fa17/" target="_blank">Algorithms for Natural Language Processing</a></h5>
        <h6 class="card-subtitle font-italic">Fall 2017: TA</h6>
      </div>
      <div class="col-sm-2 text-sm-right">
        <span class="badge" style="background-color:var(--global-theme-color); opacity:0.8">
          11-711
        </span>
      </div>
    </div>
    <ul class="card-text font-weight-light list-group list-group-flush">
      <li class="list-group-item">
        <div class="row">
          <div class="col-sm-10">
            Recitation: Conditional Random Fields
          </div>
          <div class="col-sm-2">
            <a href="http://www.cs.cmu.edu/afs/cs/user/tbergkir/www/11711fa17/recitation5_slides.pdf" target="_blank">slides</a>&nbsp;
          </div>
        </div>
      </li>
      <li class="list-group-item">
        <div class="row">
          <div class="col-sm-10">
            Recitation: Coarse-to-fine CKY parsing
          </div>
          <div class="col-sm-2">
            <a href="http://www.cs.cmu.edu/afs/cs/user/tbergkir/www/11711fa17/recitation8_notes_coarse_to_fine.pdf" target="_blank">notes</a>&nbsp;
          </div>
        </div>
      </li>
      <li class="list-group-item">
        <div class="row">
          <div class="col-sm-10">
            Recitation: EM algorithm for word alignment
          </div>
          <div class="col-sm-2">
            <a href="http://www.cs.cmu.edu/afs/cs/user/tbergkir/www/11711fa17/recitation10_slides.pdf" target="_blank">slides</a>&nbsp;            
          </div>
        </div>
      </li>  
    </ul>
    
  </div>
</div> -->

<!-- <div class="talks">
  <h3>Invited talks</h3>
  <ol class="bibliography">
    <li><div class="row">
  <div class="col-sm-8">
      <div class="title">Learning Computational Models of Non-Standard Language</div>
      <div class="periodical">    
        <em>MCQLL lab meeting, McGill University,</em> February 8, 2022        
      </div>
    <div class="links"> 
      <a class="btn btn-sm z-depth-0 abstract" role="button">Abstract</a>
      <a href="/~mryskina/assets/pdf/Ryskina-MCQLL-slides.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank">Slides</a>
    </div> 
    <div class="abstract hidden">
      <p>Non-standard linguistic items, such as novel words or creative spellings, are common in domains like social media and pose challenges for automatically processing text from these domains. To build models capable of processing such innovative items, we need to not only understand how humans reason about non-standard language, but also be able to operationalize this knowledge to create useful inductive biases. In this talk, I will present empirical studies of several phenomena under the umbrella of non-standard language, modeled at the levels of granularity ranging from individual users to entire dialects. First, I will show how idiosyncratic spelling preferences reveal information about the user, with an application to the bibliographic task of identifying typesetters of historical printed documents. Second, I will discuss the common patterns in user-specific orthographies and demonstrate that incorporating these patterns helps with unsupervised conversion of idiosyncratically romanized text into the native orthography of the language. In the final part of the talk, I will focus on word emergence in a dialect as a whole and present a diachronic corpus study modeling the language-internal and language-external factors that drive neology.</p>
    </div>   
  </div>
  </div>
  </li>
  <li><div class="row">
  <div class="col-sm-8">
      <div class="title">Romanization with Friends: Deciphering Informally Romanized Text</div>
      <div class="periodical">    
        <em>NLP with Friends seminar series,</em> November 3, 2021        
      </div>
    <div class="links"> 
      <a class="btn btn-sm z-depth-0 abstract" role="button">Abstract</a>
      <a href="https://nlpwithfriends.com/speakers/maria-ryskina" class="btn btn-sm z-depth-0" role="button" target="_blank">Website</a>
      <a href="/~mryskina/assets/pdf/Ryskina-NLPWithFriends-slides.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank">Slides</a>
      <a href="https://youtu.be/fSEyOeTpv5c" class="btn btn-sm z-depth-0" role="button" target="_blank">Video</a>
    </div> 
    <div class="abstract hidden">
      <p>Informal romanization is an idiosyncratic way of typing non-Latin-script languages in Latin alphabet, common on social media and in other online communication. Although each user has their own character substitution preferences, these choices are typically grounded in shared perceptions of visual and phonetic similarity between characters. In this talk, I will focus on the task of converting such romanized text into its native orthography for Russian, Egyptian Arabic, and Kannada, showing how similarity-encoding inductive bias helps in the absence of parallel data. I’ll also share some insights into the behaviors of the unsupervised finite-state and seq2seq models for this task and discuss how their combinations can leverage their different strengths.</p>
    </div>   
  </div>
  </div>
  </li>
  <li><div class="row">
  <div class="col-sm-8">
      <div class="title">Unsupervised Decipherment of Informal Romanization</div>
      <div class="periodical">    
        <em>NLPhD speaker series, Saarland University,</em> June 22, 2021        
      </div>
    <div class="links">
      <a class="btn btn-sm z-depth-0 abstract" role="button">Abstract</a> 
      <a href="/~mryskina/assets/pdf/Ryskina-NLPhD-slides.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank">Slides</a>
    </div>
    <div class="abstract hidden">
      <p>Informal romanization is an idiosyncratic way of typing non-Latin-script languages in Latin alphabet, commonly used in online communication. Although the character substitution choices vary between users, they are typically grounded in shared notions of visual and phonetic similarity between characters. In this talk, I will focus on the task of converting such romanized text into its native orthography for Russian, Egyptian Arabic, and Kannada, showing how similarity-encoding inductive bias helps in the absence of parallel data. I'll also share some insights into the behaviors of the unsupervised finite-state and seq2seq models for this task and discuss how their combinations can leverage their different strengths.</p>
    </div>     
  </div>
  </div>
  </li>
  <li><div class="row">
  <div class="col-sm-8">
      <div class="title">Informal Romanization across Languages and Scripts</div>
      <div class="periodical">    
        <em>SIGTYP lecture series,</em> June 18, 2021        
      </div>
    <div class="links"> 
      <a class="btn btn-sm z-depth-0 abstract" role="button">Abstract</a>
      <a href="https://sigtyp.github.io/lectures.html#lecture-ryskina" class="btn btn-sm z-depth-0" role="button" target="_blank">Website</a>
      <a href="/~mryskina/assets/pdf/Ryskina-SIGTYP-slides.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank">Slides</a>
      <a href="https://www.youtube.com/watch?v=ZCgbancq4zc&list=PLFIGad0NI4ovlwmNdHMVGnEVt3lnXUim6" class="btn btn-sm z-depth-0" role="button" target="_blank">Video</a>
    </div> 
    <div class="abstract hidden">
      <p>Informal romanization is an idiosyncratic way of typing non-Latin-script languages in Latin alphabet, commonly used in online communication. Although the character substitution choices vary between users, they are typically grounded in shared notions of visual and phonetic similarity between characters. In this talk, I will focus on the task of converting such romanized text into its native orthography and present experimental results for Russian, Arabic, and Kannada, highlighting the differences specific to writing systems. I will also show how similarity-encoding inductive bias helps in the absence of parallel data, present comparative error analysis for unsupervised finite-state and seq2seq models for this task, and explore how the combinations of the two model classes can leverage their different strengths.</p>
    </div>   
  </div>
  </div>
  </li>
</ol>
</div> -->

