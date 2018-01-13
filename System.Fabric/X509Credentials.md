<Type Name="X509Credentials" FullName="System.Fabric.X509Credentials">
  <TypeSignature Language="C#" Value="public sealed class X509Credentials : System.Fabric.SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit X509Credentials extends System.Fabric.SecurityCredentials" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.X509Credentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class X509Credentials&#xA;Inherits SecurityCredentials" />
  <TypeSignature Language="F#" Value="type X509Credentials = class&#xA;    inherit SecurityCredentials" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.SecurityCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Gibt die Sicherheitsanmeldeinformationen, die auf x. 509-Zertifikate basieren.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509Credentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.X509Credentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt eine neue Instanz der <see cref="T:System.Fabric.X509Credentials" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.AllowedCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.AllowedCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated by RemoteCommonNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Vom RemoteCommonNames als veraltet klassifiziert.</para>
        </summary>
        <value>
          <para>Die zulässigen allgemeinen Namen, die Service Fabric überprüft werden sollen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindType">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.X509FindType FindType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Security.Cryptography.X509Certificates.X509FindType FindType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.FindType" />
      <MemberSignature Language="VB.NET" Value="Public Property FindType As X509FindType" />
      <MemberSignature Language="F#" Value="member this.FindType : System.Security.Cryptography.X509Certificates.X509FindType with get, set" Usage="System.Fabric.X509Credentials.FindType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509FindType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> Gibt an, wie lokales Zertifikat im Zertifikatspeicher nicht gefunden. Unterstützte Werte: FindByThumbprint: Suchen von Zertifikat ThumbprintFindBySubjectName: finden Sie Zertifikat Allgemeine Namen oder die definierter Antragstellername aus, wenn definierten Betreffnamens verwendet wird, bereitgestellt Antragstellername im Zertifikat in "findValue" muss in ASN, die aufgrund einer Einschränkung in der systemeigenen Windows CryptoAPI-Codierung codiert werden. Es ist keine derartige Einschränkung bei der allgemeine Name im "findValue" angegeben ist.</para>
        </summary>
        <value>
          <para>Der Typ der Sicherheitsanmeldeinformationen zu verwenden, um den Cluster zu sichern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindValue">
      <MemberSignature Language="C#" Value="public object FindValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FindValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.FindValue" />
      <MemberSignature Language="VB.NET" Value="Public Property FindValue As Object" />
      <MemberSignature Language="F#" Value="member this.FindValue : obj with get, set" Usage="System.Fabric.X509Credentials.FindValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Filterwert verwendet, um das lokales Zertifikat im Zertifikatspeicher gesucht werden soll. FindType gibt den Typ des Filters an.</para>
        </summary>
        <value>
          <para>Der Wert der Anmeldeinformationen zu verwenden, um den Cluster zu sichern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindValueSecondary">
      <MemberSignature Language="C#" Value="public object FindValueSecondary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FindValueSecondary" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.FindValueSecondary" />
      <MemberSignature Language="VB.NET" Value="Public Property FindValueSecondary As Object" />
      <MemberSignature Language="F#" Value="member this.FindValueSecondary : obj with get, set" Usage="System.Fabric.X509Credentials.FindValueSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab, oder legt ihn fest den sekundären Suchwert zum Laden von lokalen Zertifikatanmeldeinformationen.</para>
        </summary>
        <value>
          <para>Die sekundäre Datenbank ermittelt den Wert für das Laden von lokalen Zertifikatanmeldeinformationen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IssuerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IssuerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.IssuerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IssuerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.IssuerThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Wenn Sie nicht leer ist, bestimmt dieser den Zertifikatfingerabdruck des direkten Aussteller des remote-Zertifikate.</para>
        </summary>
        <value>
          <para>Der Zertifikatfingerabdruck des direkten Aussteller des remote-Zertifikate.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Fabric.ProtectionLevel with get, set" Usage="System.Fabric.X509Credentials.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Zeichenfolgenwert, der verwendet wird, um anzugeben, ob die Nachrichten in der Kopfzeile und dem Textkörper besitzen, Integrität und Vertraulichkeit Garantien, die angewendet werden, wenn sie zwischen den Knoten eines Clusters gesendet werden.</para>
        </summary>
        <value>
          <para>Der Zeichenfolgenwert, der verwendet wird, um anzugeben, ob die Nachrichten in der Kopfzeile und dem Textkörper besitzen, Integrität und Vertraulichkeit Garantien, die angewendet werden, wenn sie zwischen den Knoten eines Clusters gesendet werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteCertThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; RemoteCertThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; RemoteCertThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.RemoteCertThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteCertThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.RemoteCertThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.RemoteCertThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der remote zertifikatfingerabdrücke verwendet, um remote X509Credentials überprüfen</para>
        </summary>
        <value>
          <para>Liste der remote zertifikatfingerabdrücke verwendet, um remote X509Credentials überprüfen</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; RemoteCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; RemoteCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.RemoteCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.RemoteCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.RemoteCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt an, die erwartete allgemeinen Namen der remote-Zertifikate, die Service Fabric überprüft werden sollen.</para>
        </summary>
        <value>
          <para>Die erwartete allgemeinen Namen der remote-Zertifikate, die Service Fabric überprüft werden sollen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteX509Names">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.X509Name&gt; RemoteX509Names { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.X509Name&gt; RemoteX509Names" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.RemoteX509Names" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteX509Names As IList(Of X509Name)" />
      <MemberSignature Language="F#" Value="member this.RemoteX509Names : System.Collections.Generic.IList&lt;System.Fabric.X509Name&gt;" Usage="System.Fabric.X509Credentials.RemoteX509Names" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.X509Name&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der X509Name remote X509Credentials überprüfen</para>
        </summary>
        <value>
          <para>die Liste der X509Name remote X509Credentials überprüfen</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.StoreLocation StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Security.Cryptography.X509Certificates.StoreLocation StoreLocation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As StoreLocation" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : System.Security.Cryptography.X509Certificates.StoreLocation with get, set" Usage="System.Fabric.X509Credentials.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.StoreLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Speicherort des Zertifikatspeichers.</para>
        </summary>
        <value>
          <para>Der Speicherort des Zertifikatspeichers.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="System.Fabric.X509Credentials.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Namen des Speichers, in dem das Zertifikat gespeichert wird.</para>
        </summary>
        <value>
          <para>Der Name des Speichers, in dem das Zertifikat gespeichert wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreNameDefault">
      <MemberSignature Language="C#" Value="public static string StoreNameDefault { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string StoreNameDefault" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.StoreNameDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property StoreNameDefault As String" />
      <MemberSignature Language="F#" Value="member this.StoreNameDefault : string" Usage="System.Fabric.X509Credentials.StoreNameDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt den Standardnamen des Speichers, in dem das Zertifikat gespeichert wird.</para>
        </summary>
        <value>
          <para>Der Standardname des Speichers, in dem das Zertifikat gespeichert wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>