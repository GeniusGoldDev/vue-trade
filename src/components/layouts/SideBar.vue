<template>
    <div class="col-lg-3">
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
                FUTURES
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              aria-labelledby="headingOne"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                <table class="table table-hover">
                  <thead>
                    <tr>
                      <th class="text-white fw-semibold">USOIL</th>
                      <th class="text-end">78.69</th>
                      <th class="text-end">0.71</th>
                      <th class="text-end">0.91%</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td class="text-white fw-semibold">GOLD</td>
                      <td class="text-end">2023.16</td>
                      <td class="text-danger text-end">
                        -2.73 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-danger">-0.14%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">SILVER</td>
                      <td class="text-end">22.81</td>
                      <td class="text-danger text-end">
                        -0.069 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-warning">-0.30%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">EURUSD</td>
                      <td class="text-end">1.0812</td>
                      <td class="text-danger text-end">
                        -0.000064 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-info">-0.06%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">GBPUSD</td>
                      <td class="text-end">1.2633</td>
                      <td class="text-success text-end">
                        -0.00036 <i class="mdi mdi-arrow-up"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-success">-0.03%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">USDJPY</td>
                      <td class="text-end">150.52</td>
                      <td class="text-success text-end">
                        0.247 <i class="mdi mdi-arrow-up"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-warning">0.16%</label>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingTwo">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
                FOREX
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              aria-labelledby="headingTwo"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                <table class="table table-hover">
                  <thead>
                    <tr>
                      <th class="text-white fw-semibold">USOIL</th>
                      <th class="text-end">78.69</th>
                      <th class="text-end">0.71</th>
                      <th class="text-end">0.91%</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td class="text-white fw-semibold">GOLD</td>
                      <td class="text-end">2023.16</td>
                      <td class="text-danger text-end">
                        -2.73 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-danger">-0.14%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">SILVER</td>
                      <td class="text-end">22.81</td>
                      <td class="text-danger text-end">
                        -0.069 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-warning">-0.30%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">EURUSD</td>
                      <td class="text-end">1.0812</td>
                      <td class="text-danger text-end">
                        -0.000064 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-info">-0.06%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">GBPUSD</td>
                      <td class="text-end">1.2633</td>
                      <td class="text-success text-end">
                        -0.00036 <i class="mdi mdi-arrow-up"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-success">-0.03%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">USDJPY</td>
                      <td class="text-end">150.52</td>
                      <td class="text-success text-end">
                        0.247 <i class="mdi mdi-arrow-up"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-warning">0.16%</label>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingThree">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                CRYPTO
              </button>
            </h2>
            <div
              id="collapseThree"
              class="accordion-collapse collapse"
              aria-labelledby="headingThree"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body">
                <table class="table table-hover">
                  <thead>
                    <tr>
                      <th class="text-white fw-semibold">USOIL</th>
                      <th class="text-end">78.69</th>
                      <th class="text-end">0.71</th>
                      <th class="text-end">0.91%</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td class="text-white fw-semibold">GOLD</td>
                      <td class="text-end">2023.16</td>
                      <td class="text-danger text-end">
                        -2.73 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-danger">-0.14%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">SILVER</td>
                      <td class="text-end">22.81</td>
                      <td class="text-danger text-end">
                        -0.069 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-warning">-0.30%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">EURUSD</td>
                      <td class="text-end">1.0812</td>
                      <td class="text-danger text-end">
                        -0.000064 <i class="mdi mdi-arrow-down"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-info">-0.06%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">GBPUSD</td>
                      <td class="text-end">1.2633</td>
                      <td class="text-success text-end">
                        -0.00036 <i class="mdi mdi-arrow-up"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-success">-0.03%</label>
                      </td>
                    </tr>
                    <tr>
                      <td class="text-white fw-semibold">USDJPY</td>
                      <td class="text-end">150.52</td>
                      <td class="text-success text-end">
                        0.247 <i class="mdi mdi-arrow-up"></i>
                      </td>
                      <td class="text-end">
                        <label class="badge badge-warning">0.16%</label>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
  </template>
  
  <script>
  export default {
    name: 'SideBar',
  };
  </script>
  