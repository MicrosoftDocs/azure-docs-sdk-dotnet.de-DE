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
    <summary>Ein Konfigurationselement, das die Beschränkungen der Komplexität von SOAP-Meldungen definiert, die von mit einer Bindung konfigurierten Endpunkten verarbeitet werden können. Diese Klasse kann nicht vererbt werden.</summary>
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
        <summary>Ruft ab oder legt die maximal zulässige Arraylänge.</summary>
        <value>Die maximal zulässige Arraylänge.</value>
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
        <summary>Ruft ab oder legt die maximale zulässige Anzahl von Bytes, die bei jedem Lesevorgang zurückgegeben.</summary>
        <value>Die maximal zulässige Anzahl von Bytes, die bei jedem Lesevorgang zurückgegeben.</value>
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
        <summary>Ruft ab oder legt die maximale geschachtelte Knotentiefe für jeden Lesevorgang.</summary>
        <value>Die maximale geschachtelte Knotentiefe für jeden Lesevorgang.</value>
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
        <summary>Ruft ab oder legt die maximale Anzahl von Zeichen in einem Tabellennamen zulässig.</summary>
        <value>Die maximale Anzahl von Zeichen in einem Tabellennamen zulässig.</value>
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
        <summary>Ruft ab oder legt die maximale Anzahl von Zeichen in XML-Elementinhalten zulässig.</summary>
        <value>Die maximale Anzahl von Zeichen in XML-Elementinhalten zulässig.</value>
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
            Ruft die Auflistung von Eigenschaften ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>