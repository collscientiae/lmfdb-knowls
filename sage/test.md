title: Sage cell knowl
authors:
    swisherh
    JenniferBalakrishnan
    john.jones
    schilly

<div id="replaceme">
This is a knowl which produces a Sage Cell Server.  For technical reasons, it
should always be called with at least one parameter such as n=1.  One can specify
sage code to be preloaded into the cell with an argument such as code='2^123'.
</div>

<script type="text/javascript">
  
  initcode = "";
  

  
  langs = sagecell.allLanguages;
  

  if(typeof sagecellknowlcount == "undefined") {
    sagecellknowlcount = 0;
  } else {
    sagecellknowlcount += 1;
  }
  $('#replaceme').replaceWith('<div id="myin'+sagecellknowlcount+'">loading...</div>');
  sagecell.makeSagecell({inputLocation: '#myin'+sagecellknowlcount,
        languages: langs,
        replaceOutput: true,
        code: initcode,
        linked: true,
        autoeval: true,
        hide: ['messages', 'computationID', 'files', 'sageMode','sessionFiles',
               'editorToggle', 'sessionTitle', 'done', 'permalinks'],
        evalButtonText: 'Evaluate',
      })



</script>
This is a Sage cell knowl: a <a knowl="lmfdb/doc.knowl">knowl</a> which produces a <a knowl="lmfdb/sage.cell">Sage Cell Server</a>.
