<center>
![nalgebra](img/logo_nalgebra.svg)
</center>
<br/>
<center>
[![Join us on Discord](https://img.shields.io/discord/507548572338880513.svg?logo=discord&colorB=7289DA)](https://discord.gg/vt9DJSW)
[![Travis.ci Status](https://travis-ci.org/rustsim/nalgebra.svg?branch=master)](https://travis-ci.org/rustsim/nalgebra)
[![Crates.io Status](https://meritbadge.herokuapp.com/nalgebra)](https://crates.io/crates/nalgebra)
[![License (3-Clause BSD)](https://img.shields.io/badge/license-BSD%203--Clause-blue.svg?style=flat)](https://opensource.org/licenses/BSD-3-Clause)
<div style="text-align:center">
<br/>
<a href="https://www.patreon.com/bePatron?u=7111380" ><img src="../img/become_a_patron_button.png" alt="Become a Patron!" /></a>
</div>

-----

<span class="h1 headline">Linear algebra library</span>
<div></div>
<span class="subheadline">… for the [Rust](https://www.rust-lang.org) programming language.</span>
</center>

<br>

<table markdown="1">
  <tr>
      <td>[![](../img/reference.svg)](../quick_reference)</td>
      <td style="vertical-align:middle">
      <a href="../quick_reference" id="no_highlight">
      <div>
      <big>**Quick reference**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      A [global view](../quick_reference) of all the types, functions, and methods.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/lego.svg)](../vectors_and_matrices)</td>
      <td style="vertical-align:middle">
      <a href="../vectors_and_matrices" id="no_highlight">
      <div>
      <big>**Vectors and matrices**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      The fundamental building blocks of any linear algebra library. Includes
      both heap-allocated and stack-allocated objects parametrized by their
      dimensions using type-level integers.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/decomposition.svg)](../decompositions_and_lapack)</td>
      <td style="vertical-align:middle">
      <a href="../decompositions_and_lapack" id="no_highlight">
      <div>
      <big>**Decompositions, linear solvers, and Lapack**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Compute decompositions, eigenvalues, and solutions to linear systems.
      Benefit from efficient implementations calling Lapack bindings from the
      **nalgebra-lapack** crate.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/rotation.svg)](../points_and_transformations)</td>
      <td style="vertical-align:middle">
      <a href="../points_and_transformations" id="no_highlight">
      <div>
      <big>**Points and transformations**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Types wrapping matrices and vectors to represent geometric entities
      like point and the most common transformations like rotations,
      isometries, and similarities.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/camera.svg)](../projections)</td>
      <td style="vertical-align:middle">
      <a href="../projections" id="no_highlight">
      <div>
      <big>**Projections**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Orthographic and perspective projections that agree with
      computer-graphics conventions.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/cupcake.svg)](../cg_recipes)</td>
      <td style="vertical-align:middle">
      <a href="../cg_recipes" id="no_highlight">
      <div>
      <big>**Recipes for Computer Graphics**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      How to translate/rotate a `Matrix4`. How to build a Model-View-Projection
      matrix. How to get shader-compliant object representations, etc.
      </div>
      </a>
      </td>
  </tr>
  
  <tr>
      <td>[![](../img/logo_glm.svg)](../nalgebra_glm)</td>
      <td style="vertical-align:middle">
      <a href="../nalgebra_glm" id="no_highlight">
      <div>
      <big>**A simplified API for computer graphics**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Use the **nalgebra-glm** crate for a simpler, straight-to-the-point, graphics programming-oriented functions operating
      on **nalgebra** types. This is inspired by the great C++ GLM library.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/performance.svg)](../performance_tricks)</td>
      <td style="vertical-align:middle">
      <a href="../performance_tricks" id="no_highlight">
      <div>
      <big>**Performance tricks**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Types that may help you achieve better perfomances.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/cpu.svg)](../wasm_and_embedded_programming)</td>
      <td style="vertical-align:middle">
      <a href="../wasm_and_embedded_programming" id="no_highlight">
      <div>
      <big>**Wasm and Embedded programming**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Use and compile nalgebra for browser applications or targets that do not support
      the Rust standard library.
      </div>
      </a>
      </td>
  </tr>

  <tr>
      <td>[![](../img/genericity.svg)](../generic_programming)</td>
      <td style="vertical-align:middle">
      <a href="../generic_programming" id="no_highlight">
      <div>
      <big>**Generic programming**</big>
      <span class="home_dummy_link">&nbsp;<i class="fa fa-external-link" aria-hidden="true"></i></span>
      <br>
      Use or implement traits to write your own algorithms that may be generic
      wrt. the vector space and its dimension, the transformation types, etc.
      </div>
      </a>
      </td>
  </tr>
</table>

