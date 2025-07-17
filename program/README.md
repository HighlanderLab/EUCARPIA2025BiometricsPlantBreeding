
# Scientific program
There will be nine session as shown below. We envisage that each session will have one plenary and four contributed talks.

<style>
      table {
            width: 100%;
            max-width: 1200px;
            border-collapse: collapse;
            margin: 20px 100px;
            padding: 0;
            background-color:rgba(244, 244, 244, 0);
            box-shadow: 0 0px 0px rgba(0, 0, 0, 0.2);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        th {
            color:rgb(20, 19, 21);
            font-size: 18px;
        }
        .session {
            color: #4a148c;
        }
        .break {
            color: #1a237e;
        }
        .social {
            font-weight: bold;
            color:rgb(17, 18, 80);
        }
        .embed_container {
            display: flex;
            flex-direction: column;
            align-items: center;
            background:rgba(203, 173, 216, 0.7);
            padding: 10px;
            margin-top: 5px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            cursor: pointer;
            position: relative;
        }
        .embed_title {
            flex-direction: column;
            margin-bottom: 0px;
            margin-top: -10px;
            background:rgb(143, 94, 163);
            color: white;
            padding: 5px 10px;
            border-radius: 8px;
            white-space: normal;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            font-size: 14px;
            text-align: center; 
            line-height: 1.4; 
            font-weight: bold;
            width: 110%;
        }
        .embed_item {
            margin: 5px 0;
            font-size: 14px;
            /* font-weight: bold; */
        }
        .poster_container {
            display: flex;
            flex-direction: column;
            align-items: center;
            background:rgba(178, 185, 232, 0.7);
            padding: 10px;
            margin-top: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            position: relative;
        }
        .poster_title {
            margin-bottom: 5px;
            background:rgb(80, 92, 170);
            color: white;
            padding: 2px 15px;
            border-radius: 10px;
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            white-space: nowrap;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        .poster_item {
            margin: 5px 0;
            font-weight: bold;
        }
        @media (max-width: 600px) {
            table {
                font-size: 14px;
            }
        }
/* Modal styling */
  #modal {
    display: none;
    position: fixed;
    z-index: 9999;
    left: 60px; top: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.4);
    justify-content: center;
    align-items: center;
  }
  #modalContent {
    background: white;
    padding: 20px;
    border-radius: 10px;
    min-width: 300px;
    max-width: 650px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.3);
    text-align: left;
  }
  #modalContent h2 {
    margin-top: 0;
    font-size: 20px;
    color: #4a148c;
  }
  #modalContent h3 {
    font-size: 16px;
    margin: 10px 0;
    color: #4a148c;
  }
  #modalContent p {
    font-size: 16px;
    margin: 10px 0;
  }
  #modalButton span {
    padding: 6px 12px;
    margin-top: 10px;
    background-color: #4a148c;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
</style>

<table>
        <tr>
            <th style="width: 200px;">Time</th>
            <th style="width: 300px;">Wednesday</th>
            <th style="width: 300px;">Thursday</th>
            <th style="width: 300px;">Friday</th>
        </tr>
        <tr><td>08:00-08:30</td><td>Registration</td><td rowspan="2" colspan="2"></td></tr>
        <tr><td>08:30-08:50</td><td rowspan="2">Welcome</td></tr>
        <tr><td>08:50-09:00</td><td colspan="2">Welcome</td></tr>
        <tr>
            <td>09:00-09:40</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 1: Impact of biometrics in public and private breeding programs', '9-9:40am: Gary Ailin, Bill & Melinda Gates Foundation', 'title of talk','9:40-9:55am: talker', 'title of talk','9:55-10:10am: talker', 'title of talk','10:10-10:25am: talker', 'title of talk','10:25-9:40am: talker', 'title of talk')">
                    <div class="embed_title">Gary Atlin</div>
                    <div class="embed_item">Impact of biometrics in public and private breeding programs</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 5: Genotype performance, stability and resilience', '9-9:40am: Andrea Wilson, University of Edinburgh', 'title of talk','9:40-9:55am: talker', 'title of talk','9:55-10:10am: talker', 'title of talk','10:10-10:25am: talker', 'title of talk','10:25-9:40am: talker', 'title of talk')">
                    <div class="embed_title" >Andrea Wilson</div>
                    <div class="embed_item">Genotype performance, stability and resilience</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 7: High-throughput phenotyping', '9-9:40am: María Xosé Rodríguez-Álvarez, University of Vigo', 'title of talk','9:40-9:55am: talker', 'title of talk','9:55-10:10am: talker', 'title of talk','10:10-10:25am: talker', 'title of talk','10:25-9:40am: talker', 'title of talk')">
                    <div class="embed_title" >María Xosé Rodríguez-Álvarez</div>
                    <div class="embed_item">High-throughput phenotyping</div>
                </div>
            </td>
        </tr>
        <tr>
        <td>09:40-10:10</td>
        </tr>
        <tr>
        <td>10:10-10:40</td>
        </tr>
        <tr><td>10:40-11:10</td><td class="break" colspan="3">Morning Tea (30 minutes)</td></tr>
         <tr>
            <td>11:10-11:50</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 2: Design of experiments and multi-environment trials', '11:10-11:50am: Rosemary Bailey, University of St Andrews', 'Designs with more than one blocking system: the conflict between valid randomization and latinization','11:50-12:05am: talker', 'title of talk','12:05-12:20am: talker', 'title of talk','12:20-12:35am: talker', 'title of talk','12:35-12:50am: talker', 'title of talk')">
                    <div class="embed_title">Rosemary Bailey</div>
                    <div class="embed_item">Design of experiments and multi-environment trials</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 6: Modelling and leveraging genotype by environment interaction', '11:10-11:50am: Steven Penfield, John Innes Centre', 'title of talk','11:50-12:05am: talker', 'title of talk','12:05-12:20am: talker', 'title of talk','12:20-12:35am: talker', 'title of talk','12:35-12:50am: talker', 'title of talk')">
                    <div class="embed_title">Steven Penfield</div>
                    <div class="embed_item">Modelling and leveraging genotype by environment interaction</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 8: Artificial Intelligence and machine learning in practice', '11:10-11:50am: Julian Taylor, University of Adelaide', 'title of talk','11:50-12:05am: talker', 'title of talk','12:05-12:20am: talker', 'title of talk','12:20-12:35am: talker', 'title of talk','12:35-12:50am: talker', 'title of talk')">
                    <div class="embed_title" >Julian Taylor</div>
                    <div class="embed_item">Artificial Intelligence and machine learning in practice</div>
                </div>
            </td>
        </tr>
        <tr>
        <td>11:50-12:20</td>
        </tr>
        <tr>
        <td>12:20-12:50</td>
        </tr>
        <tr><td>12:50-13:20</td><td class="break"  rowspan="2">Lunch (1 hour)</td><td class="break">Pick up lunch before social events</td><td class="break"  rowspan="2">Lunch  (1 hour)</td></tr>
        <tr><td>13:20-13:50</td><td class="break"  rowspan="9">
        <div>
        Social Program
        </div>
        </td></tr>
        <tr>
            <td>13:50-14:30</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 3: Genetic and genomic modelling of plant breeding data', '13:50-14:30pm: Pascal Schopp, KWS Group', 'A genomic selection reality check from industry: what moves the needle in genetic gain','14:30-14:45pm: talker', 'title of talk','14:45-15:00pm: talker', 'title of talk','15:00-15:15pm: talker', 'title of talk','15:15-15:30pm: talker', 'title of talk')">
                    <div class="embed_title" >Pascal Schopp</div>
                    <div class="embed_item">Genetic and genomic modelling of plant breeding data</div>
                </div>
            </td>
            <td class="session" rowspan="3">
                <div class="embed_container" rowspan="3" onclick="openModal('Session 9: Managing genetic diversity and maximising long-term genetic gains', '13:50-14:30pm: Keith Gardner, CIMMYT', 'title of talk','14:30-14:45pm: talker', 'title of talk','14:45-15:00pm: talker', 'title of talk','15:00-15:15pm: talker', 'title of talk','15:15-15:30pm: talker', 'title of talk')">
                    <div class="embed_title" >Keith Gardner</div>
                    <div class="embed_item">Managing genetic diversity and maximising long-term genetic gains</div>
                </div>
            </td>
        </tr>
        <tr>
        <td>14:30-15:00</td>
        </tr>
        <tr>
        <td>15:00-15:30</td>
        </tr>
        <tr><td>15:30-16:00</td><td class="break">Afternoon Tea (30 mins)</td><td class="break" rowspan="5">Conference Ends</td></tr>
        <tr>
            <td>16:00-16:40</td>
            <td class="session" rowspan="3">
                <div class="embed_container" onclick="openModal('Session 4: Innovative models with unconventional data streams', '16:00-16:40pm: Hao Cheng, UC Davis', 'title of talk','16:40-16:55pm: talker', 'title of talk','16:55-17:10pm: talker', 'title of talk','17:10-17:25pm: talker', 'title of talk','17:25-17:40pm: talker', 'title of talk')">
                    <div class="embed_title" >Hao Cheng</div>
                    <div class="embed_item">Innovative models with unconventional data streams </div>
                </div>
            </td>
        </tr>
        <tr>
        <td>16:40-17:10</td>
        </tr>
        <tr>
        <td>17:10-17:40</td>
        </tr>
        <tr><td>17:40-</td>
        <td class="break">
        <div class="poster_container">
          <div class="poster_item">Poster Session</div>
        </div>
        </td>
        </tr>
    </table>

<!-- Modal -->
<div id="modal">
  <div id="modalContent">
    <h2 id="modalTitle">Title</h2>
    <h3 id="modalSubtitle0">talk 0</h3>
    <h3 id="modalDetails0" style="padding-left: 2em;font-weight: bold;">title of talk 0</h3>
    <p id="modalSubtitle1" style="font-weight: bold;">talk 1</p>
    <p id="modalDetails1" style="padding-left: 2em;">title of talk 1</p>
    <p id="modalSubtitle2" style="font-weight: bold;">talk 2</p>
    <p id="modalDetails2" style="padding-left: 2em;">title of talk 2</p>
    <p id="modalSubtitle3" style="font-weight: bold;">talk 3</p>
    <p id="modalDetails3" style="padding-left: 2em;">title of talk 3</p>
    <p id="modalSubtitle4" style="font-weight: bold;">talk 4</p>
    <p id="modalDetails4" style="padding-left: 2em;">title of talk 4</p>
    <div id="modalButton" onclick="closeModal()">
    <span style="display:inline-block; margin-top:10px; padding:6px 12px; background:#ccc; border-radius:4px; cursor:pointer;">
      Close
    </span>
    </div>
  </div>
</div>

<script>
  function openModal(title, subtitle0, details0,subtitle1, details1,subtitle2, details2,subtitle3, details3,subtitle4, details4) {
    document.getElementById('modalTitle').innerText = title;
    document.getElementById('modalSubtitle0').innerText = subtitle0;
    document.getElementById('modalDetails0').innerText = details0;
    document.getElementById('modalSubtitle1').innerText = subtitle1;
    document.getElementById('modalDetails1').innerText = details1;
    document.getElementById('modalSubtitle2').innerText = subtitle2;
    document.getElementById('modalDetails2').innerText = details2;
    document.getElementById('modalSubtitle3').innerText = subtitle3;
    document.getElementById('modalDetails3').innerText = details3;
    document.getElementById('modalSubtitle4').innerText = subtitle4;
    document.getElementById('modalDetails4').innerText = details4;
    document.getElementById('modal').style.display = 'flex';
  }

  function closeModal() {
    document.getElementById("modal").style.display = "none";
  }
</script>