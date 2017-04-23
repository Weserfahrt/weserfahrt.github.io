---
title: "Anmeldung1"
background: bg2.jpg
noreadmore: true
---
Anmeldungen zur Fahrt sind hier ab sofort möglich. Bitte füllen Sie das Online-Formular vollständig aus und senden es ab. Sie erhalten dann zeitnah eine Anmeldebestätigung mit weiteren Einzelheiten.

Meldeschluss ist der 31.Mai 2017 oder bei Erreichen der Teilnehmeranzahl.

<a href="" onclick="populate_and_open_modal(event, 'modal-content-anmeldung');" class="btn btn-outline-inverse btn-sm">Online - Anmeldung</a>

<div class="content-to-populate-in-modal" id="modal-content-anmeldung">
<h3>Anmeldeformular</h3>
                  <form class="form-style validate-form clearfix" action="https://formspree.io/gerd.bode@twg1861.de" method="POST" role="form">
                  <!-- input type="hidden" name="_cc" value="gbode@freenet.de" / -->
                  <!-- input type="hidden" name="_subject" value="Weserfahrt – Online-Anmeldung" / -->
                    <div class="col-md-12">
<!-- Name, Vorname: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="string" id="form-name" placeholder="Name, Vorname" name="name" type="text" required="true">
                      </div>
<!-- Verein: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="string" id="form-name" placeholder="Verein" name="verein" type="text" required="true">
                      </div>
<!-- Anschrift: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="string" id="form-name" placeholder="Anschrift" name="anschrift" type="text" required="true">
                      </div>
<!-- Telefon: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="phone" id="form-name" placeholder="(Mobil-) Telefon" name="telefon" type="text" required="true">
                      </div>
<!-- E-Mail: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="email" id="form-email" placeholder="Email" name="email" type="email">
                      </div>
</div>
<div class="row">
<!-- Anzahl Teilnehmer: -->
<div class="col-md-5">
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="number" id="form-name" placeholder="Anzahl Teilnehmer" name="teilnehmer" type="text" required="true">
                      </div>
</div>
<div class="col-md-7">
<!-- Vor-, Zuname/ Alter*: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="string" id="form-name" placeholder="Vor-, Zuname, T-Shirt Größe/ Alter*" name="teilnehmer1" type="text" required="true">
                      </div>
<!-- Vor-, Zuname/ Alter*: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field" data-validation-type="string" id="form-name" placeholder="Vor-, Zuname, T-Shirt Größe/ Alter*" name="teilnehmer2" type="text">
                      </div>
<!-- Vor-, Zuname/ Alter*: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field" data-validation-type="string" id="form-name" placeholder="Vor-, Zuname, T-Shirt Größe/ Alter*" name="teilnehmer3" type="text">
                      </div>
<!-- Vor-, Zuname/ Alter*: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field" data-validation-type="string" id="form-name" placeholder="Vor-, Zuname, T-Shirt Größe/ Alter*" name="teilnehmer4" type="text">
                      </div>
<p>* Angaben bei Jugendlichen erforderlich</p>
</div>
</div>

<!-- Anzahl Boote/ Bootstyp: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="string" id="form-name" placeholder="Anzahl Boote/ Bootstyp" name="boote.bootstyp" type="text" required="true">
                      </div>
<!-- Anzahl Zelte: -->
                      <div class="form-group">
                        <input class="text-field form-control validate-field required" data-validation-type="number" id="form-name" placeholder="Anzahl Zelte" name="zelte" type="text" required="true">
                      </div>
<div>Teilnahme an folgender Strecke:
	 <div class="radio">
	  <label><input type="radio" name="tour" value="tour1" id="tour1"/><span>Tour 1: Oberweser – Hann. Münden bis Minden</span></label>
 	  <label><input type="radio" name="tour" value="tour2" id="tour2"/><span>Tour 2: Oberweser/Mittelweser – Hann. Münden bis Bremen</span></label>
	  <label><input type="radio" name="tour" value="tour3" id="tour3"/><span>Tour 3: Kurs Nord – Hann. Münden bis Nordenham</span></label>
	</div>
	<!-- some troll discards values here, see JS in footer.html -->
</div>
<hr/>
<div>
<h5>freiwillige Angaben</h5>
<p>In meinem PKW biete ich Platz für Mitfahrer, Zelte und Boote
<input class="text-field form-control validate-field form-inline" data-validation-type="string" id="form-name" placeholder="Kennzeichen" name="kfz" type="text"><br> 
<input class="text-field form-control validate-field form-inline" data-validation-type="number" id="form-name" placeholder="Anzahl Mitfahrer" name="pkw.angebot.mitfahrer" type="text"><br>
<input class="text-field form-control validate-field form-inline" data-validation-type="number" id="form-name" placeholder="Anzahl Boote" name="pkw.angebot.boote" type="text"><br>
<input class="text-field form-control validate-field form-inline" data-validation-type="number" id="form-name" placeholder="Anzahl Zelte" name="pkw.angebot.zelte" type="text"><br>
<input class="text-field form-control validate-field" data-validation-type="string" id="form-name" placeholder="Abfahrtsort" name="pkw.angebot.abfahrtsort" type="text">
</p>
</div>
<hr/>

                      <div class="form-group">
                        <textarea placeholder="Bemerkungen" class="form-control validate-field" name="bemerkungen"></textarea>
                      </div>
<p>Sie erhalten in den nächsten Tagen per Email eine Bestätigung der sie auch die Zahlungsmodalitäten entnehmen. Erst mit Erhalt dieser Email und vorbehaltlich des Zahlungseingangs gilt ihre Anmeldung als verbindlich.</p>
                      <div class="form-group">
                        <img src="assets/images/theme_images/loader-form.GIF" class="form-loader">
                        <button type="submit" class="btn btn-sm btn-outline-inverse btn-lg btn-block" style="font-size:1em;">Senden</button>
                      </div>
                      <div class="form-group form-general-error-container"></div>           
                  
