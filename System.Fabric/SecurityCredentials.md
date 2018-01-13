<Type Name="SecurityCredentials" FullName="System.Fabric.SecurityCredentials">
  <TypeSignature Language="C#" Value="public abstract class SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SecurityCredentials" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityCredentials" />
  <TypeSignature Language="F#" Value="type SecurityCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Eine abstrakte Basisklasse für Typen, die Anmeldeinformationen für die Sicherheit darstellen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CredentialType">
      <MemberSignature Language="C#" Value="public System.Fabric.CredentialType CredentialType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.CredentialType CredentialType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SecurityCredentials.CredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property CredentialType As CredentialType" />
      <MemberSignature Language="F#" Value="member this.CredentialType : System.Fabric.CredentialType with get, set" Usage="System.Fabric.SecurityCredentials.CredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Typ der Sicherheitsanmeldeinformationen verwenden, um den Cluster – secure gültige Werte sind "none", "X509", "Windows".</para>
        </summary>
        <value>
          <para>Der Typ der Sicherheitsanmeldeinformationen verwenden, um den Cluster zu sichern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.SecurityCredentials LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.SecurityCredentials LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SecurityCredentials.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.SecurityCredentials" Usage="System.Fabric.SecurityCredentials.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para>Die aktuelle Codepaket-Aktivierungskontext <see cref="T:System.Fabric.CodePackageActivationContext" />.</para>
        </param>
        <param name="configPackageName">
          <para>Die aktuelle Konfiguration Paketname.</para>
        </param>
        <param name="sectionName">
          <para>Dem Abschnitt in der Konfigurationsdatei, die die Sicherheitseinstellungen definiert.</para>
        </param>
        <summary>
          <para>Instanziieren <see cref="T:System.Fabric.SecurityCredentials" /> Objekt aus den Einstellungen für die Dienstkonfigurationsdatei</para>
        </summary>
        <returns>Die Anmeldeinformationen.</returns>
        <remarks>
          <para> Einstellungen enthält die Konfigurationsdatei ("Settings.xml") innerhalb der Service-Konfigurationsordner sollten alle Sicherheitseinstellungen, die zum Erstellen erforderlich ist <see cref="T:System.Fabric.SecurityCredentials" /> Objekt, und übergeben Sie an die <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> Methode.
            In der Regel bleibt auf den dienstautor, lesen Sie die Datei "Settings.xml", analysieren Sie die Werte aus, und erstellen entsprechend der <see cref="T:System.Fabric.SecurityCredentials" /> Objekt.</para>
          <para>Mit der aktuellen Hilfsmethode kann den oben aufgeführten Vorgang dienstautor umgangen werden.</para>
          <para>Es folgen die Namen der Parameter, die in der Dienstkonfiguration "settings.xml" von Windows Fabric, um die oben genannten Analyse automatisch erkannt werden bereitgestellt werden sollten:</para>
          <list type="number">
            <item>
              <description>
                <para>CredentialType – Typ der Anmeldeinformationen zum sicheren Kommunikationskanals mit: X509 (X509 zertifikatsanmeldeinformationen) oder Windows (Windows-Anmeldeinformationen, erfordert active Directory)</para>
              </description>
            </item>
          </list>
          <para> CredentialType = X509</para>
          <list type="number">
            <item>
              <description>
                <para>StoreLocation-Speicherort, um das Zertifikat zu suchen: CurrentUser oder LocalMachine</para>
              </description>
            </item>
            <item>
              <description>
                <para>"StoreName"-Name des Zertifikatspeichers, in dem das Zertifikat gesucht werden sollen</para>
              </description>
            </item>
            <item>
              <description>
                <para>FindType-identifiziert den Typ des Werts, der im Parameter "findValue" gebotenen: FindBySubjectName oder FindByThumbPrint</para>
              </description>
            </item>
            <item>
              <description>
                <para>Ziel von "findValue" als Suchkriterium für die Suche nach dem Zertifikat</para>
              </description>
            </item>
            <item>
              <description>
                <para>AllowedCommonNames eine durch Trennzeichen getrennte Liste der allgemeinen Namen/DNS-Namen. Diese Liste sollten alle Zertifikate, die von Replikatoren verwendet, es wird verwendet, um eingehende Zertifikat zu überprüfen.</para>
              </description>
            </item>
            <item>
              <description>
                <para>IssuerThumbprints eine kommagetrennte Liste der zertifikatfingerabdrücke Aussteller. Wenn angegeben, wird das eingehende Zertifikat überprüft, wenn er durch einen der Einträge in der Liste, zusätzlich zur Überprüfung der Zertifikatkette ausgegeben wird.</para>
              </description>
            </item>
            <item>
              <description>
                <para>RemoteCertThumbprints eine durch Trennzeichen getrennte Liste der zertifikatfingerabdrücke. Diese Liste sollten alle Zertifikate, die von Replikatoren verwendet, es wird verwendet, um eingehende Zertifikat zu überprüfen.</para>
              </description>
            </item>
            <item>
              <description>
                <para>ProtectionLevel – gibt an, wie die Daten geschützt: anmelden oder EncryptAndSign oder None.</para>
              </description>
            </item>
          </list>
          <para> CredentialType = Windows</para>
          <list type="number">
            <item>
              <description>
                <para>ServicePrincipalName Service Principal Name, die für den Dienst registriert. Kann leer sein, wenn der Dienst/Akteur Hostprozesse als ein Computerkonto ausgeführt wird (z. B.: "NetworkService" usw. "LocalSystem".)</para>
              </description>
            </item>
            <item>
              <description>
                <para>WindowsIdentities eine kommagetrennte Liste der Windows-Identitäten aller Service/Akteur Host Prozesse.</para>
              </description>
            </item>
            <item>
              <description>
                <para>ProtectionLevel – gibt an, wie die Daten geschützt: anmelden oder EncryptAndSign oder None.</para>
              </description>
            </item>
          </list>
          <para>X509 Ausschnitt Konfigurationsbeispiel</para>
          <code>
            &lt;Name des Abschnitts "SecurityConfig" =&gt; &lt;Parametername = "CredentialType" Value = "X509" /&gt; &lt;Parametername = "FindType" Value = "FindByThumbprint" /&gt; &lt;Parametername = " "FindValue""Wert =" 9D c9 06 b1 69 dc 4f af fd 16 97 Ac 78 1e 80 67 90 74 9 d 2f "/&gt; &lt;Parametername ="StoreLocation"Value ="LocalMachine"/&gt; &lt;Parametername ="StoreName"Value ="My"/ &lt; c9 &gt; &gt;  &lt;Parametername = "ProtectionLevel" Value = "EncryptAndSign" /&gt; &lt;Parametername = "AllowedCommonNames" Value="My-Test-SAN1-Alice,My-Test-SAN1-Bob" /&gt; &lt;/ Im Abschnitt&gt;
              </code>
          <para>Codeausschnitt für die Windows-Konfiguration, Beispiel 1: der Dienst/Akteur-Hostprozesse als "NetworkService" oder "LocalSystem" ausgeführt.</para>
          <code>&lt;Name des Abschnitts "SecurityConfig" =&gt; &lt;Parametername = "CredentialType" Value = "Windows" /&gt; &lt;Parametername = "ServicePrincipalName" Value = "" /&gt; &lt;!--dieses Computers Gruppe enthält alle Computer in einem Cluster –&gt; &lt;Parametername = "WindowsIdentities" Value = "Redmond\ClusterMachineGroup" /&gt; &lt;Parametername = "ProtectionLevel" Value = "EncryptAndSign "/&gt;  &lt; /Section&gt;</code>
          <para>Codeausschnitt für die Windows-Konfiguration, Beispiel 1: alle Service/Akteur Hostprozesse als gruppenverwaltete Dienstkonto ausgeführt.</para>
          <code>&lt;Name des Abschnitts "SecurityConfig" =&gt; &lt;Parametername = "CredentialType" Value = "Windows" /&gt; &lt;Parametername = "ServicePrincipalName" Value="servicefabric/cluster.microsoft.com" /&gt; &lt;– Alle Akteur-Dienst-Hostprozesse ausführende Redmond\GroupManagedServiceAccount--&gt; &lt;Parametername = "WindowsIdentities" Value = "Redmond\GroupManagedServiceAccount" /&gt; &lt;Parametername = "ProtectionLevel" Value = "EncryptAndSign" /&gt;  &lt; /Section&gt;</code>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>