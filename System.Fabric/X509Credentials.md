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
      <para><span data-ttu-id="7912d-101">Gibt die Sicherheitsanmeldeinformationen, die auf x. 509-Zertifikate basieren.</span><span class="sxs-lookup"><span data-stu-id="7912d-101">Specifies the security credentials that are based upon X.509 certificates.</span></span></para>
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
          <para><span data-ttu-id="7912d-102">Erstellt eine neue Instanz der <see cref="T:System.Fabric.X509Credentials" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7912d-102">Creates a new instance of the <see cref="T:System.Fabric.X509Credentials" /> class.</span></span></para>
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
          <para><span data-ttu-id="7912d-103">Vom RemoteCommonNames als veraltet klassifiziert.</span><span class="sxs-lookup"><span data-stu-id="7912d-103">Deprecated by RemoteCommonNames.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-104">Die zulässigen allgemeinen Namen, die Service Fabric überprüft werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7912d-104">The allowed common names that you want Service Fabric to validate against.</span></span></para>
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
          <para> <span data-ttu-id="7912d-105">Gibt an, wie lokales Zertifikat im Zertifikatspeicher nicht gefunden. Unterstützte Werte: FindByThumbprint: Suchen von Zertifikat ThumbprintFindBySubjectName: finden Sie Zertifikat Allgemeine Namen oder die definierter Antragstellername aus, wenn definierten Betreffnamens verwendet wird, bereitgestellt Antragstellername im Zertifikat in "findValue" muss in ASN, die aufgrund einer Einschränkung in der systemeigenen Windows CryptoAPI-Codierung codiert werden.</span><span class="sxs-lookup"><span data-stu-id="7912d-105">Specifies how to find local certificate in certificate store.Supported values:FindByThumbprint: find certificate by certificate thumbprintFindBySubjectName: find certificate by subject distinguished name or common name, when subject distinguished name is provided in FindValue, subject name in the certificate must be encoded in ASN encoding due to a restriction in native Windows crypto API.</span></span> <span data-ttu-id="7912d-106">Es ist keine derartige Einschränkung bei der allgemeine Name im "findValue" angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="7912d-106">There is no such restriction when common name is provided in FindValue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-107">Der Typ der Sicherheitsanmeldeinformationen zu verwenden, um den Cluster zu sichern.</span><span class="sxs-lookup"><span data-stu-id="7912d-107">The type of security credentials to use to secure the cluster.</span></span></para>
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
          <para><span data-ttu-id="7912d-108">Gibt den Filterwert verwendet, um das lokales Zertifikat im Zertifikatspeicher gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="7912d-108">Specifies the filter value used to search local certificate in certificate store.</span></span> <span data-ttu-id="7912d-109">FindType gibt den Typ des Filters an.</span><span class="sxs-lookup"><span data-stu-id="7912d-109">FindType specifies the type of filter value.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-110">Der Wert der Anmeldeinformationen zu verwenden, um den Cluster zu sichern.</span><span class="sxs-lookup"><span data-stu-id="7912d-110">The value of security credentials to use to secure the cluster.</span></span></para>
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
          <para><span data-ttu-id="7912d-111">Ruft ab, oder legt ihn fest den sekundären Suchwert zum Laden von lokalen Zertifikatanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="7912d-111">Gets or sets the secondary find value for loading local certificate credential.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-112">Die sekundäre Datenbank ermittelt den Wert für das Laden von lokalen Zertifikatanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="7912d-112">The secondary find value for loading local certificate credential.</span></span></para>
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
          <para><span data-ttu-id="7912d-113">Wenn Sie nicht leer ist, bestimmt dieser den Zertifikatfingerabdruck des direkten Aussteller des remote-Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="7912d-113">When not empty, this dictates the certificate thumbprints of direct issuer of remote certificates.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-114">Der Zertifikatfingerabdruck des direkten Aussteller des remote-Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="7912d-114">The certificate thumbprints of direct issuer of remote certificates.</span></span></para>
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
          <para><span data-ttu-id="7912d-115">Gibt den Zeichenfolgenwert, der verwendet wird, um anzugeben, ob die Nachrichten in der Kopfzeile und dem Textkörper besitzen, Integrität und Vertraulichkeit Garantien, die angewendet werden, wenn sie zwischen den Knoten eines Clusters gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="7912d-115">Indicates the string value that is used to specify whether the messages in the header and body have integrity and confidentiality guarantees applied to them when they are sent between the nodes of a cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-116">Der Zeichenfolgenwert, der verwendet wird, um anzugeben, ob die Nachrichten in der Kopfzeile und dem Textkörper besitzen, Integrität und Vertraulichkeit Garantien, die angewendet werden, wenn sie zwischen den Knoten eines Clusters gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="7912d-116">The string value that is used to specify whether the messages in the header and body have integrity and confidentiality guarantees applied to them when they are sent between the nodes of a cluster.</span></span></para>
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
          <para><span data-ttu-id="7912d-117">Ruft die Liste der remote zertifikatfingerabdrücke verwendet, um remote X509Credentials überprüfen</span><span class="sxs-lookup"><span data-stu-id="7912d-117">Gets the list of remote certificate thumbprints, used to validate remote X509Credentials</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-118">Liste der remote zertifikatfingerabdrücke verwendet, um remote X509Credentials überprüfen</span><span class="sxs-lookup"><span data-stu-id="7912d-118">List of remote certificate thumbprints, used to validate remote X509Credentials</span></span></para>
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
          <para><span data-ttu-id="7912d-119">Gibt an, die erwartete allgemeinen Namen der remote-Zertifikate, die Service Fabric überprüft werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7912d-119">Indicates the expected common names of remote certificates that you want Service Fabric to validate against.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-120">Die erwartete allgemeinen Namen der remote-Zertifikate, die Service Fabric überprüft werden sollen.</span><span class="sxs-lookup"><span data-stu-id="7912d-120">The expected common names of remote certificates that you want Service Fabric to validate against.</span></span></para>
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
          <para><span data-ttu-id="7912d-121">Ruft die Liste der X509Name remote X509Credentials überprüfen</span><span class="sxs-lookup"><span data-stu-id="7912d-121">Gets the list of X509Name to validate remote X509Credentials</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-122">die Liste der X509Name remote X509Credentials überprüfen</span><span class="sxs-lookup"><span data-stu-id="7912d-122">the list of X509Name to validate remote X509Credentials</span></span></para>
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
          <para><span data-ttu-id="7912d-123">Gibt den Speicherort des Zertifikatspeichers.</span><span class="sxs-lookup"><span data-stu-id="7912d-123">Indicates the location of the certificate store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-124">Der Speicherort des Zertifikatspeichers.</span><span class="sxs-lookup"><span data-stu-id="7912d-124">The location of the certificate store.</span></span></para>
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
          <para><span data-ttu-id="7912d-125">Gibt den Namen des Speichers, in dem das Zertifikat gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="7912d-125">Indicates the name of the store where the certificate is stored.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-126">Der Name des Speichers, in dem das Zertifikat gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="7912d-126">The name of the store where the certificate is stored.</span></span></para>
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
          <para><span data-ttu-id="7912d-127">Gibt den Standardnamen des Speichers, in dem das Zertifikat gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="7912d-127">Indicates the default name of the store where the certificate is stored.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7912d-128">Der Standardname des Speichers, in dem das Zertifikat gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="7912d-128">The default name of the store where the certificate is stored.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>