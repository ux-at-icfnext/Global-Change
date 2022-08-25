
<ul class="usa-card-group">
  {% for card in page.cards %}
    <li class="usa-card {{card.class | default: 'tablet:grid-col-4'}}">
      <div class="usa-card__container">
        <div class="usa-card__header">
          <p>
            <small class="tags">{{card.tags}}</small>
          </p>
          <h2 class="usa-card__heading">{{card.title}}</h2>
        </div>
        {% if card.img %}
            <div class="usa-card__media {{card.media-class}}">
                <div class="usa-card__img">
                <img
                    src="{{card.img}}"
                    alt="{{card.alt}}"
                />
                </div>
            </div>
        {% endif %}
      <div class="usa-card__body">
        <p class="italics">
          {{card.italics}}
        </p>
        <p>
            {{card.content}}
        </p>
      </div>
      <div class="usa-card__footer">
        <button class="usa-button">{{card.button}}</button>
      </div>
    </div>
  </li>
  {% endfor %}
</ul>