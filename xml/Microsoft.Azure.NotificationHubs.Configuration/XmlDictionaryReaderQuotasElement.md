<Type Name="XmlDictionaryReaderQuotasElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement">
  <TypeSignature Language="C#" Value="public sealed class XmlDictionaryReaderQuotasElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit XmlDictionaryReaderQuotasElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class XmlDictionaryReaderQuotasElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type XmlDictionaryReaderQuotasElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="61379-101">Ein Konfigurationselement, das die Beschränkungen der Komplexität von SOAP-Meldungen definiert, die von mit einer Bindung konfigurierten Endpunkten verarbeitet werden können.</span><span class="sxs-lookup"><span data-stu-id="61379-101">A configuration element that defines the constraints on the complexity of SOAP messages that can be processed by endpoints configured with a binding.</span></span> <span data-ttu-id="61379-102">Diese Klasse kann nicht vererbt werden.</span><span class="sxs-lookup"><span data-stu-id="61379-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public XmlDictionaryReaderQuotasElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="61379-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61379-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxArrayLength">
      <MemberSignature Language="C#" Value="public int MaxArrayLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxArrayLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxArrayLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxArrayLength As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxArrayLength : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxArrayLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxArrayLength", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="61379-104">Ruft ab oder legt die maximal zulässige Arraylänge.</span><span class="sxs-lookup"><span data-stu-id="61379-104">Gets or sets the maximum allowed array length.</span></span></summary>
        <value><span data-ttu-id="61379-105">Die maximal zulässige Arraylänge.</span><span class="sxs-lookup"><span data-stu-id="61379-105">The maximum allowed array length.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBytesPerRead">
      <MemberSignature Language="C#" Value="public int MaxBytesPerRead { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBytesPerRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxBytesPerRead" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBytesPerRead As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBytesPerRead : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxBytesPerRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBytesPerRead", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="61379-106">Ruft ab oder legt die maximale zulässige Anzahl von Bytes, die bei jedem Lesevorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="61379-106">Gets or sets the maximum allowed number of bytes returned for each read.</span></span></summary>
        <value><span data-ttu-id="61379-107">Die maximal zulässige Anzahl von Bytes, die bei jedem Lesevorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="61379-107">The maximum allowed number of bytes returned for each read.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDepth">
      <MemberSignature Language="C#" Value="public int MaxDepth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDepth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxDepth" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDepth As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDepth : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxDepth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxDepth", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="61379-108">Ruft ab oder legt die maximale geschachtelte Knotentiefe für jeden Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="61379-108">Gets or sets the maximum nested node depth for each read.</span></span></summary>
        <value><span data-ttu-id="61379-109">Die maximale geschachtelte Knotentiefe für jeden Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="61379-109">The maximum nested node depth for each read.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNameTableCharCount">
      <MemberSignature Language="C#" Value="public int MaxNameTableCharCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxNameTableCharCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxNameTableCharCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxNameTableCharCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxNameTableCharCount : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxNameTableCharCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxNameTableCharCount", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="61379-110">Ruft ab oder legt die maximale Anzahl von Zeichen in einem Tabellennamen zulässig.</span><span class="sxs-lookup"><span data-stu-id="61379-110">Gets or sets the maximum number of characters allowed in a table name.</span></span></summary>
        <value><span data-ttu-id="61379-111">Die maximale Anzahl von Zeichen in einem Tabellennamen zulässig.</span><span class="sxs-lookup"><span data-stu-id="61379-111">The maximum number of characters allowed in a table name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxStringContentLength">
      <MemberSignature Language="C#" Value="public int MaxStringContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxStringContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxStringContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxStringContentLength As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxStringContentLength : int with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.MaxStringContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxStringContentLength", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="61379-112">Ruft ab oder legt die maximale Anzahl von Zeichen in XML-Elementinhalten zulässig.</span><span class="sxs-lookup"><span data-stu-id="61379-112">Gets or sets the maximum number of characters allowed in XML element content.</span></span></summary>
        <value><span data-ttu-id="61379-113">Die maximale Anzahl von Zeichen in XML-Elementinhalten zulässig.</span><span class="sxs-lookup"><span data-stu-id="61379-113">The maximum number of characters allowed in XML element content.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.XmlDictionaryReaderQuotasElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61379-114">Ruft die Auflistung von Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="61379-114">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>