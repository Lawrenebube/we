<script setup>
  // import horse from "../assets/images/felix.jpg"
  import horse from "../assets/images/horsecard.JPG";


</script>

<template>
  <main>
   
    <div class="blackSection1">
        <section class="section1">
          <h2>Taste Maker</h2>
          <h3>Meet Atlas Supper Club.</h3>
          <p>
            Skip past the endless waitlists and concierge calls that turn up empty handed. With Atlas,
            you have a seat at the table at today's most desirable restaurants.
          </p>
          <img :src="horse" alt="a red horse with wings"/>
          <!-- <img :src="require('@/assets/image.jpg')" alt="Webpack Handled Image"> -->
        </section>
        <section class="writeblock">
          <aside>Dedicated reservations¹</aside>
          <p>
            Access exclusive inventory at our restaurant partners including – Horses, Felix Trattoria,
            Cucina Alba, and more.
          </p>
        </section>
        <section class="writeblock">
          <aside>Last-minute bookings²</aside>
          <p>With bookings available at short notice, you won't find yourself on a waitlist.</p>
        </section>
        <section class="writeblock">
          <aside>Access during peak hours</aside>
          <p>Members get seated at prime time, when availability is typically the hardest to get.</p>
        </section>
        <div class="images3">
          <div class="bottle">
            <!-- <img src="../assets/images/horses.JPG" alt="a served table with a plate of noodles with a knife and fork, an empty class cup and an opened bottle" /> -->
            <p>HORSES, LA, ON ATLAS SUPPER CLUB.</p>
          </div>
          <div>
            <!-- <img src="../assets/images/felix.jpg" alt="" /> -->
            <p>FELIX TRATTORIA, LA, ON ATLAS SUPPER CLUB.</p>
          </div>
          <div>
            <!-- <img src="../assets/images/cucina.jpg" alt="" /> -->
            <p>CUCINA ALBA, NYC, ON ATLAS SUPPER CLUB.</p>
          </div>
        </div>
      </div>

  </main>

  <footer>
    <div>
      <ol>
        <li>
          ATLAS SUPPER CLUB RESERVATIONS ARE AVAILABLE ON A FIRST COME, FIRST SERVE BASIS
          EXCLUSIVELY TO ATLAS CARDHOLDERS FROM WITHIN ATLAS APP. THE ATLAS SUPPER CLUB CODE OF
          CONDUCT <a href="">(ATLASCARD.COM/CODE-OF-CONDUCT)</a> AND THE CANCELLATION POLICY OF THE
          APPLICABLE RESTAURANT APPLY FOR EACH RESERVATION. LISTED RESTAURANTS ARE SUBJECT TO CHANGE
          AT ANY TIME WITHOUT PRIOR NOTICE.
        </li>
        <li>LAST-MINUTE RESERVATIONS SUBJECT TO AVAILABILITY.</li>
        <li>
          5X POINTS WITH BLADE APPLIES TO ALL ELIGIBLE BLADE SERVICES. 5X POINTS IS CALCULATED AND
          APPLIED AT THE END OF STATEMENT PERIODS THAT INCLUDE SETTLED BLADE TRANSACTIONS.
        </li>
        <li>
          PROVIDED AS A $189 STATEMENT CREDIT TO YOUR ATLAS ACCOUNT UPON PURCHASE OF CLEAR PLUS
          ANNUAL MEMBERSHIP WITH YOUR ATLAS CARD. VISIT <a href="">ENROLL.CLEARME.COM/ENROLL/</a> TO
          LEARN MORE.
        </li>
        <li>
          ATLAS CARDHOLDERS ARE ELIGIBLE TO RECEIVE REIMBURSEMENT FOR UP TO $600 PER YEAR OF
          CANCELLATION/CHANGE FEE INCURRED WITH RESPECT TO ELIGIBLE AIRFARE PURCHASES THAT ARE
          CANCELED FOR ANY REASON, FOR WHICH REIMBURSEMENT IS SOUGHT BEFORE THE BENEFIT END DATE,
          AND IF THE ELIGIBLE CARDHOLDER IS NOT ELIGIBLE TO RECEIVE A REIMBURSEMENT FROM ANOTHER
          SOURCE.
        </li>
        <li>VISIT <a href="">HTTPS://ATLASCARD.COM/VISA-INFINITE</a> TO LEARN MORE.</li>
        <li>YOUR PHYSICAL CARD DETAILS ARE AVAILABLE TO ACCESS ANY TIME WITHIN ATLAS APP.</li>
        <li>
          REWARDED CATEGORIES ELIGIBLE FOR 3X POINTS UPGRADE INCLUDE DINING, FLIGHTS, HOTELS,
          RIDESHARES, NIGHTLIFE, FASHION, GROCERIES, WELLNESS, HEALTH, HOME, AND AUTO SERVICES. 3X
          POINTS UPGRADE IS CALCULATED AND APPLIED AT THE END OF EACH STATEMENT PERIOD ON SETTLED
          TRANSACTIONS WITHIN YOUR TOP REWARDED CATEGORY BY DOLLAR AMOUNT. OUTSIDE OF THE TOP SPEND
          CATEGORY, SETTLED TRANSACTIONS FOR PRODUCTS AND SERVICES PROVIDED BY MERCHANTS AND/OR
          CATEGORIES NOT SUBJECT TO ANOTHER POINTS MULTIPLIER, WILL ACCRUE 1 POINT FOR EVERY DOLLAR
          SPENT (1X POINTS) AFTER THE APPLICABLE BILLING CYCLE. SUBJECT TO RESTRICTIONS AND THE
          REWARDS & BENEFIT TERMS.
        </li>
        <li>
          CREATE UNLIMITED NEW CARDS WITHIN ATLAS APP, WITH UP TO FIVE ACTIVE CARDS AT ANY ONE TIME.
        </li>
        <li>
          CARDHOLDER IS RESPONSIBLE FOR THE COST OF PURCHASES OF GOODS AND SERVICES AND/OR THIRD
          PARTY EXPENSES AND SERVICES INCURRED IN RELATION TO ANY FULFILLED REQUESTS.
        </li>
        <li>
          PROVIDED AS A $199 STATEMENT CREDIT TO YOUR ATLAS ACCOUNT UPON PURCHASE OF ONE MEDICAL
          ANNUAL MEMBERSHIP WITH YOUR ATLAS CARD. VISIT <a href="">ONEMEDICAL.COM/ATLAS/</a> TO
          LEARN MORE.
        </li>
        <li>
          COMPLIMENTARY $100 ANNUAL EREWHON CAFE MEMBERSHIP. BENEFIT ENROLLMENT INSTRUCTIONS
          PROVIDED IN APP.
        </li>
        <li>
          UP TO $300 IN ANNUAL STATEMENT CREDITS ($25/MONTH). GET YOUR FIRST MONTH FREE BY USING THE
          FUTURE FITNESS ATLAS CARDHOLDER ENROLLMENT PAGE. VISIT
          <a href="">FUTURE.CO/ATLASCARD</a> TO LEARN MORE.
        </li>
        <li>
          ATLAS IS A TRUE CHARGE CARD WITH NO PRE-SET SPENDING LIMITS. THIS MEANS YOUR SPENDING
          LIMIT IS FLEXIBLE. UNLIKE TRADITIONAL CARDS WITH SET LIMITS, THE AMOUNT YOU CAN SPEND
          FLEXIBLY ADAPTS BASED ON A RANGE OF FACTORS SUCH AS YOUR PURCHASES, STATEMENT BALANCE
          PAYMENTS, AND CREDIT HISTORY.
        </li>
      </ol>
    </div>
  </footer>
</template>
