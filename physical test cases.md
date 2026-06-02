1. **TC01 — Verify fan powers ON**

   * **Objective:** Check that the electric fan turns on properly.
   * **Input:** Power supply connected.
   * **Steps:**

     * Plug the fan into the socket.
     * Press the ON button.
   * **Expected:** Fan turns ON and blades start rotating.
   * **Actual:** Fan turned ON and blades started rotating.
   * **Verdict:** Pass.

2. **TC02 — Verify fan powers OFF**

   * **Objective:** Check that the electric fan turns off properly.
   * **Input:** Fan is ON.
   * **Steps:**

     * Press the OFF button.
   * **Expected:** Fan stops completely.
   * **Actual:** Fan stopped completely.
   * **Verdict:** Pass.

3. **TC03 — Verify low speed works**

   * **Objective:** Check Low speed setting.
   * **Input:** Speed setting: Low.
   * **Steps:**

     * Turn the fan ON.
     * Select Low speed.
   * **Expected:** Fan rotates slowly with stable airflow.
   * **Actual:** Fan rotated slowly with stable airflow.
   * **Verdict:** Pass.

4. **TC04 — Verify medium speed works**

   * **Objective:** Check Medium speed setting.
   * **Input:** Speed setting: Medium.
   * **Steps:**

     * Turn the fan ON.
     * Select Medium speed.
   * **Expected:** Fan rotates faster than Low speed.
   * **Actual:** Fan rotated faster than Low speed.
   * **Verdict:** Pass.

5. **TC05 — Verify high speed works**

   * **Objective:** Check High speed setting.
   * **Input:** Speed setting: High.
   * **Steps:**

     * Turn the fan ON.
     * Select High speed.
   * **Expected:** Fan rotates at maximum speed with strong airflow.
   * **Actual:** Fan rotated at maximum speed with strong airflow.
   * **Verdict:** Pass.

6. **TC06 — Verify oscillation function**

   * **Objective:** Check that the fan head moves left and right.
   * **Input:** Oscillation button ON.
   * **Steps:**

     * Turn the fan ON.
     * Press the oscillation button.
   * **Expected:** Fan head moves left and right smoothly.
   * **Actual:** Fan head moved left and right smoothly.
   * **Verdict:** Pass.

7. **TC07 — Verify oscillation can be stopped**

   * **Objective:** Check that oscillation can be turned off.
   * **Input:** Oscillation button OFF.
   * **Steps:**

     * Turn the fan ON with oscillation enabled.
     * Turn oscillation OFF.
   * **Expected:** Fan head stops moving and stays in a fixed direction.
   * **Actual:** Fan head stopped moving and stayed in a fixed direction.
   * **Verdict:** Pass.

8. **TC08 — Verify height adjustment**

   * **Objective:** Check that fan height can be adjusted.
   * **Input:** Adjustable stand.
   * **Steps:**

     * Loosen the height lock.
     * Adjust the fan height.
     * Tighten the lock.
   * **Expected:** Fan height changes and remains stable.
   * **Actual:** Fan height changed and remained stable.
   * **Verdict:** Pass.

9. **TC09 — Verify tilt adjustment**

   * **Objective:** Check that the fan head angle can be adjusted.
   * **Input:** Fan head angle.
   * **Steps:**

     * Turn the fan OFF.
     * Tilt the fan head up or down.
     * Turn the fan ON.
   * **Expected:** Fan head stays at the selected angle during operation.
   * **Actual:** Fan head stayed at the selected angle during operation.
   * **Verdict:** Pass.

10. **TC10 — Verify blade guard safety**

    * **Objective:** Check that the blade guard protects the user.
    * **Input:** Blade guard attached.
    * **Steps:**

      * Inspect the front and rear guards.
      * Gently touch the guard while the fan is running.
    * **Expected:** Guard remains fixed and prevents contact with blades.
    * **Actual:** Guard remained fixed and prevented contact with blades.
    * **Verdict:** Pass.

11. **TC11 — Verify noise level**

    * **Objective:** Check for abnormal noise or vibration.
    * **Input:** Fan running at each speed.
    * **Steps:**

      * Turn the fan ON.
      * Test Low, Medium, and High speeds.
    * **Expected:** Fan runs without abnormal noise or vibration.
    * **Actual:** Fan ran without abnormal noise or vibration.
    * **Verdict:** Pass.

12. **TC12 — Verify stability during operation**

    * **Objective:** Check that the fan remains stable while running.
    * **Input:** Fan placed on a flat surface.
    * **Steps:**

      * Place the fan on a flat floor or table.
      * Run the fan at High speed.
    * **Expected:** Fan remains stable and does not shake excessively or fall.
    * **Actual:** Fan remained stable and did not shake excessively or fall.
    * **Verdict:** Pass.

13. **TC13 — Verify heat safety**

    * **Objective:** Check that the fan does not overheat.
    * **Input:** Fan running for 30 minutes.
    * **Steps:**

      * Turn the fan ON at High speed.
      * Let it run for 30 minutes.
      * Carefully check the motor area.
    * **Expected:** Motor area may be warm but not dangerously hot; fan continues operating normally.
    * **Actual:** Motor area was warm but not dangerously hot; fan continued operating normally.
    * **Verdict:** Pass.

14. **TC14 — Verify power cord condition**

    * **Objective:** Check that the power cord and plug work safely.
    * **Input:** Power cord and plug.
    * **Steps:**

      * Inspect the power cord.
      * Plug it into the socket.
      * Move the cord slightly.
    * **Expected:** Fan remains powered; no sparks, exposed wire, or loose connection.
    * **Actual:** Fan remained powered; no sparks, exposed wire, or loose connection occurred.
    * **Verdict:** Pass.

15. **TC15 — Verify timer function**

    * **Objective:** Check timer operation, if the fan has a timer.
    * **Input:** Timer set to 30 minutes.
    * **Steps:**

      * Turn the fan ON.
      * Set timer to 30 minutes.
      * Wait until timer ends.
    * **Expected:** Fan automatically turns OFF after the selected time.
    * **Actual:** Fan automatically turned OFF after the selected time.
    * **Verdict:** Pass.
