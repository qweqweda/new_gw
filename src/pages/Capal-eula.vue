<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const APPNAME = 'Capal'
const EMAILADDRESS = 'marycitadelgabule1985@outlook.com'
</script>

<template>
  <div class="bg">
    <div class="agreement">
      <div class="T_title_main">
        END USER LICENSE AGREEMENT (EULA)
      </div>
      <div class="T_content">
        This End User License Agreement (“Agreement”) is between you (“End User”) and {{ APPNAME }} (“Licensor”). By
        downloading or using the {{ APPNAME }} application (“Licensed Application”) from Apple's App Store, you agree to
        the terms below.
      </div>
      <div class="T_content">
        Apple is not a party to this Agreement and is not responsible for the Licensed Application, its contents,
        maintenance, or support. This Agreement may not conflict with the Apple Media Services Terms and Conditions.
      </div>
      <!--  -->
      <div class="T_title_contact">
        Contact us: {{ EMAILADDRESS }}
      </div>
      <br>

      <!-- 1 -->
      <div class="T_title">
        1. The Application
      </div>
      <div class="T_content">
        Capal is a social platform for skateboarders of all levels. It enables users to connect, share skateboarding
        experiences, and learn new skills. The Licensed Application is customized for iOS devices.

      </div>

      <!-- 2 -->
      <div class="T_title">
        2. Scope of License
      </div>
      <div class="T_content">
        1 You may install and use the Licensed Application on Apple devices you own or control, consistent with
        Apple's Usage Rules.

        <br>
        2. You may not copy, modify, distribute, or sublicense the Licensed Application except as expressly permitted.
        <br>
        3. Licensor may update or modify this Agreement as needed.
        
       
      </div>

      <!-- 3 -->
      <div class="T_title">
        3. Technical Requirements
      </div>
      <div class="T_content">
        Licensor may update the Licensed Application to remain compatible with iOS and new devices, but is not obligated to provide updates.
      </div>

      <!-- 4 -->
      <div class="T_title">
        4. Maintenance and Support
      </div>
      <div class="T_content">
        Licensor is solely responsible for providing maintenance and support. Apple has no obligation to provide such services. Contact details are provided in Section 12.
      </div>

      <!-- 5 -->
      <div class="T_title">
        5. Use of Data
      </div>
      <div class="T_content">
        Licensor may collect technical data and usage information to improve products and services, consistent with its Privacy Policy. Personal data handling follows the terms of that Privacy Policy.
      </div>

      <!-- 6 -->
      <div class="T_title">
        6.User-Generated Content
      </div>
      <div class="T_content">
        Users may post content such as text, photos, or videos (“Contributions”). You are solely responsible for your Contributions and must ensure they:
 Do not infringe third-party rights.
 Are lawful and appropriate.
 Do not contain offensive or harmful material.

Licensor may remove or restrict Contributions at its discretion.
      </div>

      <!-- 7 -->
      <div class="T_title">
        7. Contribution License
      </div>
      <div class="T_content">
        By posting Contributions, you grant Licensor a worldwide, non-exclusive, royalty-free license to use, display, and distribute such content in connection with the Licensed Application. You retain ownership of your Contributions.
      </div>

      <!-- 8 -->
      <div class="T_title">
        8. Liability
      </div>
      <div class="T_content">
        Licensor is not responsible for damages arising from misuse or unauthorized modification of the Licensed Application. Backup of your data is your responsibility.
      </div>
      <!-- 9 -->
      <div class="T_title">
        9. Warranty
      </div>
      <div class="T_content">
        1. Licensor warrants that the Licensed Application is free of malware at download and functions as described.
2. No warranty applies if the Licensed Application is modified, used improperly, or combined with incompatible systems.
3. Remedies for defects are limited to repair, replacement, or refund through the App Store.
      </div>
      <div class="T_title">
        10. Product Claims
      </div>
      <div class="T_content">
       
Licensor, not Apple, is responsible for handling product liability, legal compliance, consumer protection, and other claims related to the Licensed Application.
      </div>
      <div class="T_title">
        11. Legal Compliance
      </div>
      <div class="T_content">
        You confirm that you are not located in a restricted country and are not on any U.S. Government prohibited party list.
      <div class="T_title">
        12. Contact Information
      </div>
      <div class="T_content">
       
For inquiries or claims regarding the Licensed Application, contact:

Capal
Purok 3 Gango Ozamiz City, Misamis Occidental 7200 Philippines
Email: marycitadelgabule1985@outlook.com
      </div>
      <div class="T_title">
        13. Termination
      </div>
      <div class="T_content">
        This Agreement is valid until terminated by either party. Your rights will end automatically if you fail to comply with the Agreement. Upon termination, you must cease use and delete all copies of the Licensed Application.
      </div>
      <div class="T_title">
        14. Third-Party Beneficiaries
      </div>
      <div class="T_content">
        Apple and its subsidiaries are third-party beneficiaries of this Agreement and may enforce its terms against you.
      </div>
      <div class="T_title">
        15. Intellectual Property
      </div>
      <div class="T_content">
        Licensor retains all intellectual property rights in the Licensed Application. In case of third-party claims, Licensor is solely responsible for defense and settlement.
      </div>
      <div class="T_title">
        16. Governing Law
      </div>
      <div class="T_content">
        This Agreement is governed by the laws of England and Wales, excluding conflict-of-law rules.
      </div><div class="T_title">
        17. Miscellaneous
      </div>
      <div class="T_content">
        1. If any provision is invalid, the remainder remains enforceable.
        2. Amendments must be made in writing.
      </div><div class="T_title">
        18.Subscriptions
      </div>
      <div class="T_content">
        Certain features of the Licensed Application require a paid subscription. Subscriptions automatically renew for the same duration and price unless canceled at least 24 hours before the end of the current period through your App Store account settings. All subscription terms, including pricing, duration, and cancellation, are provided in the App Store and within the Licensed Application. By using these subscription features, you agree to be bound by these terms.
      </div>
    </div>
  </div>
</div>
</template>

<style scoped>
.agreement {
  padding: 10px 20px;
  font-size: 14px;
  margin-bottom: 14px;
  color: #000;
  background-color: #fff;
  text-align: left;
}

.T_title_main {
  font-size: 30px;
  font-weight: 900;
  margin: 1rem 0px;
  color: #000;
  text-align: center;
}

.T_title {
  font-size: 18px;
  font-weight: 700;
  margin: 1rem 0px;
  color: #000;
  text-align: left;
}

.T_title_secondary {
  font-size: 16px;
  font-weight: 500;
  margin: 1rem 0px;
  color: #000;
  text-align: left;
}

.T_content {
  font-size: 14px;
  font-weight: 400;
  margin-bottom: 12px;
  color: #0e0d0d;
  text-align: left;
}

.bg {
  padding: 50px 50px;
  margin: 0;
  background-color: #f5f6f7;
  width: 100vw;
  height: 100vh;
  position: fixed;
  top: 0;
  left: 0;
  overflow-y: auto;
}

.T_title_contact {
  font-size: 24px;
  font-weight: 900;
  margin: 1rem 0px;
  color: #000;
  text-align: left;
}
</style>
