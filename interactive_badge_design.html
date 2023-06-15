<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Badge Design</title>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js"
        integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous">
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"
        integrity="sha384-fbbOQedDUMZZ5KreZpsbe1LCZPVmfTnH7ois6mU1QK+m14rQ1l2bGBq41eYeM/fS" crossorigin="anonymous">
    </script>
    <script src="https://cdn.jsdelivr.net/npm/sortablejs@latest/Sortable.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.min.js"
        integrity="sha384-fbbOQedDUMZZ5KreZpsbe1LCZPVmfTnH7ois6mU1QK+m14rQ1l2bGBq41eYeM/fS" crossorigin="anonymous">
    </script>

    <link rel="stylesheet" href="./assets/css/style.css">
    <link href='https://fonts.googleapis.com/css?family=Poppins' rel='stylesheet'>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins';
            background-color: var(--first-color-lighten);
        }

        .form-designer {
            display: grid;
        }

        .form-element {
            cursor: move;
        }

        .collapsible {
            background-color: rgba(110, 110, 110, 0.089);
            cursor: pointer;
            width: 100%;
            border: none;
            border-radius: 3px;
            align-items: center;
            text-align: center;
        }

        .active,
        .form-element:hover {
            background-color: #afafaf49;
        }

        .content {
            display: none;
            overflow: hidden;
            width: 100%;
            background-color: rgba(110, 110, 110, 0.089);
            padding: 0px 30px 15px 30px;
        }

        .content input[type="text"] {
            width: 100%;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            border: 0;
            border-radius: 5px;
            padding: 5px;
            margin-top: 5px;
        }

        .delButton {
            position: absolute;
            background-color: #ccc;
            color: rgba(39, 39, 39, 0.496);
            border: none;
            outline: none;
            top: 0;
            right: 0;
        }

        .btn-group {
            position: absolute;
            top: 0;
            right: 0;
            visibility: hidden;
            border: pink;
        }

        .prevClass {
            max-width: 100%;
            height: auto;
        }

        .badge_class {
            position: relative;
            width: 100%;
            min-width: 100%;
            margin-bottom: 10px;
        }

        .badge_class:hover {
            box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;
        }

        .badge_class:hover .btn-group {
            visibility: visible;
        }

        div.sticky {
            position: -webkit-sticky;
            position: sticky;
            top: 0;
        }

        .delBtn:hover {
            background-color: red;
            color: #fefefe;
        }

        .design-canvas {
            min-height: 750px;
            margin: 0 auto;
            background-color: transparent;
        }

        .fa-circle-question {
            color: #0d6efc;
        }

        .fa-circle-question:hover {
            color: #0d56fc;
        }

        .btn-save {
            box-shadow: 0px 5px 10px 0px rgba(0, 0, 0, 0.192);
            transition: transform ease 0.5s, box-shadow ease 0.5s;
        }

        .btn-save:hover {
            transform: translateY(-5px);
            box-shadow: 0px 10px 20px 2px rgba(0, 0, 0, 0.25);
        }
    </style>
</head>

<body class="bg-primary">
    <div class="container p-3">
        <div class="card border-0 shadow-sm">
            <div class="card-header bg-white py-3">
                <h3 class="fw-bold">Badge Design</h3>
            </div>
            <div class="card-body">
                <div class="pt-2 d-flex align-items-center">
                    <div class="me-auto">
                        <h5 class="fw-bold d-inline me-2">Design</h5>
                        <i class="fa-solid fa-circle-question fa-lg" data-bs-toggle="tooltip" data-bs-placement="right"
                            data-bs-custom-class="custom-tooltip"
                            data-bs-title="Please drag any elements from the left panel into the drop region"></i>
                    </div>
                    <button type="button" onclick="saveCoordinates()"
                        class="btn btn-primary btn-save rounded"><i class="fa-solid fa-floppy-disk fa-sm me-2"></i>Save</button>
                </div>


                <div class="d-flex justify-content-end">

                </div>
                <div class="row py-3">
                    <div class="col-lg-10 col-md-12 order-2">
                        <div id="drop-region"
                            class="drop-region bg-secondary bg-opacity-10 rounded p-3  overflow-hidden">
                            <div id="design-canvas" class="design-canvas">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2 col-md-12 order-1 mb-2">
                        <div class="sticky">
                            <div id="text-field" class="form-element border rounded-top p-1" draggable="true">Text</div>
                            <div id="image" class="form-element border rounded-bottom p-1" draggable="true">QR Code</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</body>


<script>
    let elementCounter = 1;
    let imgCounter =  1;// Initialize a counter for generating unique IDs
    
    // Drag start event handler
    function dragStart(event) {
        event.dataTransfer.setData("text/plain", event.target.id);
    }
    
    // Drop event handler
    function drop(event) {
        event.preventDefault();
        const elementId = event.dataTransfer.getData("text/plain");
        const element = document.getElementById(elementId).cloneNode(true);
        
        if (element.id === "text-field") {
        const newElement = document.createElement("div");
        newElement.classList.add("badge_class");
        const elementId = "element_" + elementCounter; // Generate a unique ID
        elementCounter++; // Increment the counter for the next element
        
        newElement.id = elementId; // Set the generated ID to the new element
        
        // Rest of the code for creating the new element...
        if (event.target === event.currentTarget) {
        const newText = document.createElement("button");
        newText.type = "button";
        newText.classList.add("collapsible");
        const newPar = document.createElement("p");
        newPar.id = "p1_" + elementId; // Update the paragraph ID
        newPar.classList.add("par_class", "mb-0", "p-2");
        newPar.textContent = "Text";
        newText.appendChild(newPar);
        
        
        
        const divGroupBtn = document.createElement("div");
        divGroupBtn.classList.add("btn-group", "justify-content-end");
        
        newElement.appendChild(divGroupBtn);
        
        const delBtn = document.createElement("button");
        delBtn.classList.add("btn", "delBtn", "btn-primary", "border", "border-0", "fas", "fa-trash-alt", "p-2");
        delBtn.addEventListener("click", function() {
        deleteElement(elementId);
        });
        
        const editBtn = document.createElement("button");
        editBtn.classList.add("btn", "editBtn", "btn-primary", "border", "border-0", "fa-sharp", "fa-solid", "fa-pen", "p-2");
        
        const parId = newPar.id;
        
        const alignLeftBtn = document.createElement("button");
        alignLeftBtn.classList.add("btn", "alignLeftBtn", "btn-primary", "border", "border-0", "fa-solid", "fa-align-left",
        "p-2");
        alignLeftBtn.value = "left";
        alignLeftBtn.addEventListener("click", function() {
        var alignval = this.value;
        var txt = document.getElementById(parId);
        txt.style.textAlign = alignval;
        
        alignLeftBtn.classList.add("active");
        alignCenterBtn.classList.remove("active");
        alignRightBtn.classList.remove("active");
        });
        
        
        const alignCenterBtn = document.createElement("button");
        alignCenterBtn.classList.add("btn", "alignCenterBtn", "btn-primary", "border", "border-0", "fa-solid",
        "fa-align-justify", "p-2");
        alignCenterBtn.value = "center";
        alignCenterBtn.addEventListener("click", function() {
        var alignval = this.value;
        var txt = document.getElementById(parId);
        txt.style.textAlign = alignval;
        alignCenterBtn.classList.add("active");
        alignLeftBtn.classList.remove("active");
        alignRightBtn.classList.remove("active");
        });
        
        const alignRightBtn = document.createElement("button");
        alignRightBtn.classList.add("btn", "alignRightBtn", "btn-primary", "border", "border-0", "fa-solid", "fa-align-right",
        "p-2");
        alignRightBtn.value = "right";
        alignRightBtn.addEventListener("click", function() {
        var alignval = this.value;
        var txt = document.getElementById(parId);
        txt.style.textAlign = alignval;
        alignRightBtn.classList.add("active");
        alignLeftBtn.classList.remove("active");
        alignCenterBtn.classList.remove("active");
        });
        
        divGroupBtn.appendChild(alignLeftBtn);
        divGroupBtn.appendChild(alignCenterBtn);
        divGroupBtn.appendChild(alignRightBtn);
        divGroupBtn.appendChild(editBtn);
        divGroupBtn.appendChild(delBtn);
        
        
        newElement.appendChild(newText);
        
        const newCon = document.createElement("div");
        const hr = document.createElement("hr");
        hr.classList.add("border", "border-secondary", "opacity-25")
        newCon.appendChild(hr);
        
        newCon.id = "txtCon_" + elementId;
        newCon.classList.add("content");
        const conName = document.createElement("label");
        conName.classList.add("mb-1")
        conName.textContent = "Content";
        newCon.appendChild(conName);
        
        const inputName = document.createElement("input");
        inputName.type = "text";
        inputName.name = "text_content";
        inputName.id = "input_name_" + elementId; // Update the input field ID
        inputName.oninput = function() {
        updateText(elementId); // Call updateText() with the corresponding elementId
        };
        newCon.appendChild(inputName);
        
        //const br = document.createElement("br");
        //newCon.appendChild(br);

        const conID = document.createElement("label");
        conID.classList.add("mt-1");
        conID.textContent = "ID";
        newCon.appendChild(conID);
        const inputTextId = document.createElement("input");
        inputTextId.type = "text";
        inputTextId.name = "text_id";
        inputTextId.value = elementId;

        newCon.appendChild(inputTextId);

        const txtwl = document.createElement("label");
        txtwl.classList.add("mt-1");
        txtwl.textContent = "Width";
        newCon.appendChild(txtwl);
        const txtw = document.createElement("input");
        txtw.type = "text";
        txtw.name = "text_width";

        newCon.appendChild(txtw);

        const txthl = document.createElement("label");
        txthl.classList.add("mt-1");
        txthl.textContent = "Height";
        newCon.appendChild(txthl);
        const txth = document.createElement("input");
        txth.type = "text";
        txth.name = "text_height";

        newCon.appendChild(txth);
        
        newElement.appendChild(newCon);
        
        //newElement.appendChild(delbut);
        
        // Attach event listeners and perform necessary actions...
        const txtID = newCon.id;
        editBtn.addEventListener("click", function() {
        this.classList.toggle("active");
        var content = document.getElementById(txtID);
        if (content.style.display === "block") {
        content.style.opacity = "0";
        content.style.display = "none";
        } else {
        content.style.display = "block";
        setTimeout(function() {
        content.style.opacity = "1";
        }, 10);
        }
        });
        
        element.replaceWith(newElement);
        event.target.appendChild(newElement);
        }

        else {
        return false;
        }


      /*===== DRAG and DROP =====*/
      const dropItems = event.target;

      console.log("p1_" + elementId);

      new Sortable(dropItems, {
        animation: 350,
        chosenClass: "sortable-chosen",
        dragClass: "sortable-drag"
      });
    

    } 
    else if (element.id === "image") {
      const qrnewElement = document.createElement("div");
      qrnewElement.classList.add("badge_class");
      const qrelementId = "qr_" + imgCounter; // Generate a unique ID
      imgCounter++; // Increment the counter for the next element
    
      qrnewElement.id = qrelementId; // Set the generated ID to the new element
    
      // Rest of the code for creating the new element...
      if (event.target === event.currentTarget) {
      const newQr = document.createElement("button");
      newQr.type = "button";
      newQr.classList.add("collapsible");
      const qrnewPar = document.createElement("p");
      qrnewPar.id = "qrp_" + qrelementId; // Update the paragraph ID
      qrnewPar.classList.add("qr_class", "mb-0", "p-2");
      qrnewPar.textContent = "QR Code";
      qrnewPar.name = "qrc";
      newQr.appendChild(qrnewPar);

      const qrdivGroupBtn = document.createElement("div");
      qrdivGroupBtn.classList.add("btn-group", "justify-content-end", "align-items-end");

      qrnewElement.appendChild(qrdivGroupBtn);

      const qreditBtn = document.createElement("button");
      qreditBtn.classList.add("btn", "editBtn", "btn-primary", "border", "border-0", "fa-sharp", "fa-solid", "fa-pen", "p-2");

      const qrdelBtn = document.createElement("button");
      qrdelBtn.classList.add("btn", "delBtn", "btn-primary", "border", "border-0", "fas", "fa-trash-alt", "p-2");
      qrdelBtn.addEventListener("click", function() {
        deleteImg(qrelementId);
      });

      qrdivGroupBtn.appendChild(qreditBtn);
      qrdivGroupBtn.appendChild(qrdelBtn);
      

      qrnewElement.appendChild(newQr);

        const newqrCon = document.createElement("div");
        const qrhr = document.createElement("hr");
        qrhr.classList.add("border", "border-secondary", "opacity-25")
        newqrCon.appendChild(qrhr);
        
        newqrCon.id = "qrCon_" + elementId;
        newqrCon.classList.add("content");
        const qrconName = document.createElement("label");
        qrconName.classList.add("mt-1");
        qrconName.textContent = "ID";
        newqrCon.appendChild(qrconName);
        
        const qrinputName = document.createElement("input");
        qrinputName.type = "text";
        qrinputName.name = "qr_id";
        //qrinputName.id = "input_name_" + elementId; // Update the input field ID
        qrinputName.value = qrelementId;
        newqrCon.appendChild(qrinputName);

        const qrwl = document.createElement("label");
        qrwl.classList.add("mt-1");
        qrwl.textContent = "Width";
        newqrCon.appendChild(qrwl);
        const qrw = document.createElement("input");
        qrw.type = "text";
        qrw.name = "qr_width";

        newqrCon.appendChild(qrw);

        const qrhl = document.createElement("label");
        qrhl.classList.add("mt-1");
        qrhl.textContent = "Height";
        newqrCon.appendChild(qrhl);
        const qrh = document.createElement("input");
        qrh.type = "text";
        qrh.name = "qr_height";

        newqrCon.appendChild(qrh);

        qrnewElement.appendChild(newqrCon);

        const qrID = newqrCon.id;
        qreditBtn.addEventListener("click", function() {
        this.classList.toggle("active");
        var content = document.getElementById(qrID);
        if (content.style.display === "block") {
        content.style.opacity = "0";
        content.style.display = "none";
        } else {
        content.style.display = "block";
        setTimeout(function() {
        content.style.opacity = "1";
        }, 10);
        }
        });



      element.replaceWith(qrnewElement);
      event.target.appendChild(qrnewElement);
    }
      /*===== DRAG and DROP =====*/
      const qrdropItems = event.target;

      new Sortable(qrdropItems, {
        animation: 350,
        chosenClass: "sortable-chosen",
        dragClass: "sortable-drag"
      });
    
          // Rest of the code...
    }
    else {
      event.target.appendChild(element);
    }
  }
    
  function updateText(elementId) {
    var inputText = document.getElementById("input_name_" + elementId).value;
    var paragraph = document.getElementById("p1_" + elementId);
    paragraph.textContent = inputText;
  }
    
  function deleteElement(elementId) {
    const element = document.getElementById(elementId);
    if (element) {
      element.remove();
    }
  }
    
  function displayImage(event, imgId) {
    var input = document.getElementById("input_img_" + imgId);
    var reader = new FileReader();
    
    reader.onload = function() {
    var image = document.getElementById("img_" + imgId);
      image.src = reader.result;
    };
    
    reader.readAsDataURL(input.files[0]);
  }
    
  function deleteImg(imgId) {
    const element = document.getElementById(imgId);
    if (element) {
      element.remove();
    }
  }
    
  // Drag over event handler
  function dragOver(event) {
    event.preventDefault();
  }
    
  // Add dragstart and dragover event listeners to form elements
  const formElements = document.querySelectorAll(".form-element");
  formElements.forEach(function(element) {
    element.addEventListener("dragstart", dragStart);
  });
    
  const dropRegion = document.getElementById("design-canvas");
  dropRegion.addEventListener("dragover", dragOver);
  dropRegion.addEventListener("drop", drop);
</script>

<script>
    function saveCoordinates() {

    var designCanvas = $( "#design-canvas" ).first();
    var designCanvas = designCanvas.position();
    
    console.log(designCanvas);
    
    let order = 0;
    const coor = [];
    const conElements = document.querySelectorAll('.badge_class');
    //let emptyanot = false;
    
    conElements.forEach(element => {
    order++;
    
    //const element_id = element.id;
    // const rect = element.getBoundingClientRect();
    var rect = $( element ).first();
    var rect = rect.position();
    // var rect = element_id.position();
    var x = Number(rect.left);
    var y = Number(rect.top);

    var coorX = designCanvas.left - x;
    var coorY = y - designCanvas.top;
    
    const tc = element.querySelector('input[name="text_content"]');
    const tc_id = element.querySelector('input[name="text_id"]');
    const qrInputId = element.querySelector('input[name="qr_id"]');
    const tw = element.querySelector('input[name="text_width"]');
    const th = element.querySelector('input[name="text_height"]');
    const qrw = element.querySelector('input[name="qr_width"]');
    const qrh = element.querySelector('input[name="qr_height"]');
    const tb = element.querySelector('.collapsible');
    const tcc = tb.querySelector('.par_class');
    const tcs = tcc ? window.getComputedStyle(tcc).textAlign : null;
    const cqr = element.querySelector('.qr_class');
    // const cqrs = window.getComputedStyle(cqr).textAlign;
    
    let content = null;
    let alignment = null;
    let element_id = null;
    let w = null;
    let h = null;

    content = "QR Code";
    alignment = "default";

    if (tc) {
      if (!Number.isInteger(x)) {
        x = Math.ceil(x); // Round up x if it's a decimal
      }

      if (!Number.isInteger(y)) {
        y = Math.ceil(y); // Round up y if it's a decimal
      }
      content = tc.value;
      alignment = tcs;
      element_id = tc_id.value;
      w = tw.value;
      h = th.value; 
    } 
    else if (cqr) {
      if (!Number.isInteger(x)) {
        x = Math.ceil(x); // Round up x if it's a decimal
      }

      if (!Number.isInteger(y)) {
        y = Math.ceil(y); // Round up y if it's a decimal
      }
      content = "QR Code";
      alignment = "default";
      element_id = qrInputId.value;
      w = qrw.value;
      h = qrh.value;
    }

    /*if (!content) {
    emptyanot = true;
    }*/
    
    const nameWithCoordinates = {
    ordering: order,
    id: element_id,
    content: content,
    alignment: alignment,
    width: w,
    height: h,
    X: coorX,
    Y: coorY,
    };
    
    coor.push(nameWithCoordinates);
    });
    
    /*if (emptyanot) {
    alert('Content is empty.');
    return;
    }*/
    
    console.log(coor);

    
    const json = JSON.stringify(coor);
    const now = new Date().toISOString().replace(/[:.]/g, '-');
    const fileName = `badge_design-${now}.json`;
    
    const blob = new Blob([json], {type: 'application/json'});
    const url = URL.createObjectURL(blob);
    
    const a = document.createElement('a');
    a.href = url;
    a.download = fileName;
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
  }

</script>

<script>
    const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]');
    const tooltipList = [...tooltipTriggerList].map(tooltipTriggerEl => new bootstrap.Tooltip(tooltipTriggerEl));
</script>


</html>