# Miembros del equipo

<style>
.miembros-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.miembro {
  margin: 0;
  text-align: center;
}

.miembro img {
  display: block;
  width: 100%;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  border-radius: 12px;
}

.miembro figcaption {
  margin-top: 0.75rem;
  font-weight: 600;
}

@media (max-width: 700px) {
  .miembros-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="miembros-grid">
  <figure class="miembro">
    <img src="../assets/miembros/jose-mesa-delgado.jpg" alt="Foto de Jose Mesa Delgado" />
    <figcaption>Jose Mesa Delgado</figcaption>
  </figure>
  <figure class="miembro">
    <img src="../assets/miembros/abel-martin-carmona_v2.jpg" alt="Foto de Abel Martin Carmona" />
    <figcaption>Abel Martin Carmona</figcaption>
  </figure>
  <figure class="miembro">
    <img src="../assets/miembros/muhammad-numan.jpg" alt="Foto de Muhhammad Numan" />
    <figcaption>Muhhammad Numan</figcaption>
  </figure>
</div>
