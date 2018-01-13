<Type Name="XmlDictionaryReaderQuotasElement" FullName="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement">
  <TypeSignature Language="C#" Value="public sealed class XmlDictionaryReaderQuotasElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit XmlDictionaryReaderQuotasElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class XmlDictionaryReaderQuotasElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type XmlDictionaryReaderQuotasElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6faf4-101">Ein Konfigurationselement, das die Beschränkungen der Komplexität von SOAP-Meldungen definiert, die von mit einer Bindung konfigurierten Endpunkten verarbeitet werden können.</span><span class="sxs-lookup"><span data-stu-id="6faf4-101">A configuration element that defines the constraints on the complexity of SOAP messages that can be processed by endpoints configured with a binding.</span></span> <span data-ttu-id="6faf4-102">Diese Klasse kann nicht vererbt werden.</span><span class="sxs-lookup"><span data-stu-id="6faf4-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public XmlDictionaryReaderQuotasElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxArrayLength">
      <MemberSignature Language="C#" Value="public int MaxArrayLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxArrayLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxArrayLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxArrayLength As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxArrayLength : int with get, set" Usage="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxArrayLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="6faf4-103">Ruft ab oder legt die maximal zulässige Arraylänge.</span><span class="sxs-lookup"><span data-stu-id="6faf4-103">Gets or sets the maximum allowed array length.</span></span></summary>
        <value><span data-ttu-id="6faf4-104">Die maximal zulässige Arraylänge.</span><span class="sxs-lookup"><span data-stu-id="6faf4-104">The maximum allowed array length.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBytesPerRead">
      <MemberSignature Language="C#" Value="public int MaxBytesPerRead { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBytesPerRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxBytesPerRead" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBytesPerRead As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBytesPerRead : int with get, set" Usage="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxBytesPerRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="6faf4-105">Ruft ab oder legt die maximale zulässige Anzahl von Bytes, die bei jedem Lesevorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6faf4-105">Gets or sets the maximum allowed number of bytes returned for each read.</span></span></summary>
        <value><span data-ttu-id="6faf4-106">Die maximal zulässige Anzahl von Bytes, die bei jedem Lesevorgang zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6faf4-106">The maximum allowed number of bytes returned for each read.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDepth">
      <MemberSignature Language="C#" Value="public int MaxDepth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDepth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxDepth" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDepth As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDepth : int with get, set" Usage="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxDepth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="6faf4-107">Ruft ab oder legt die maximale geschachtelte Knotentiefe für jeden Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="6faf4-107">Gets or sets the maximum nested node depth for each read.</span></span></summary>
        <value><span data-ttu-id="6faf4-108">Die maximale geschachtelte Knotentiefe für jeden Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="6faf4-108">The maximum nested node depth for each read.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNameTableCharCount">
      <MemberSignature Language="C#" Value="public int MaxNameTableCharCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxNameTableCharCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxNameTableCharCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxNameTableCharCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxNameTableCharCount : int with get, set" Usage="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxNameTableCharCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="6faf4-109">Ruft ab oder legt die maximale Anzahl von Zeichen in einem Tabellennamen zulässig.</span><span class="sxs-lookup"><span data-stu-id="6faf4-109">Gets or sets the maximum number of characters allowed in a table name.</span></span></summary>
        <value><span data-ttu-id="6faf4-110">Die maximale Anzahl von Zeichen in einem Tabellennamen zulässig.</span><span class="sxs-lookup"><span data-stu-id="6faf4-110">The maximum number of characters allowed in a table name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxStringContentLength">
      <MemberSignature Language="C#" Value="public int MaxStringContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxStringContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxStringContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxStringContentLength As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxStringContentLength : int with get, set" Usage="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.MaxStringContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="6faf4-111">Ruft ab oder legt die maximale Anzahl von Zeichen in XML-Elementinhalten zulässig.</span><span class="sxs-lookup"><span data-stu-id="6faf4-111">Gets or sets the maximum number of characters allowed in XML element content.</span></span></summary>
        <value><span data-ttu-id="6faf4-112">Die maximale Anzahl von Zeichen in XML-Elementinhalten zulässig.</span><span class="sxs-lookup"><span data-stu-id="6faf4-112">The maximum number of characters allowed in XML element content.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6faf4-113">Ruft die Auflistung von Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="6faf4-113">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>