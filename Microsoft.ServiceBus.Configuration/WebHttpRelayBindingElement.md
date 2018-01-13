<Type Name="WebHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class WebHttpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebHttpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WebHttpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type WebHttpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Bindungselement, das zum Konfigurieren von Endpunkten für einen Azure Service Bus-Relay-Dienst, der auf HTTP-Anforderungen und nicht durch SOAP-Nachrichten reagiert. </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des neuen Bindungselements.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />-Klasse unter Verwendung des angegebenen Namens.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("allowCookies", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Client Cookies akzeptiert und bei zukünftigen Anfragen weiterleitet.</summary>
        <value>"true", wenn Cookies zulässig sind; andernfalls "false". Der Standardwert ist false.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ der Bindung, die dieses Konfigurationselement darstellt.</summary>
        <value>Gibt eine <see cref="T:System.Type" /> , der Bindungstyp enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="webHttpRelayBindingElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> Die Bindung dieses Konfigurationselements aus aktualisiert werden soll.</param>
        <summary>Initialisiert den Inhalt dieses Bindungskonfigurationselements aus den Eigenschaftswerten einer angegebenen Bindung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("isDynamic", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob das Bindungselement, das dynamisch ist.</summary>
        <value>"true", wenn das Bindungselement, das dynamisch ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferPoolSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Speicherkapazität für den Puffer-Manager ab, der die Puffer verwaltet, die für die von dieser Bindung verwendeten Endpunkte erforderlich sind, oder legt sie fest.</summary>
        <value>Gibt die maximale Größe in Bytes des Pufferpools, die von einem mit dieser Bindung konfigurierten Endpunkt verwendet. Der Standardwert ist 65.536 Bytes.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Speicherkapazität ab, die vom Manager der Nachrichtenpuffer verwendet werden kann, die Nachrichten aus dem Kanal empfangen, oder legt diese fest.</summary>
        <value>Gibt die maximale Arbeitsspeichermenge in Bytes zur Verwendung in den Puffer-Manager zurück. Der Standardwert ist 524.288 (0x80000) Bytes.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der festgelegte Wert ist kleiner oder gleich 0.</exception>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxReceivedMessageSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die maximale Größe für eine Nachricht ab, die von der Bindung verarbeitet werden kann, oder legt sie fest.</summary>
        <value>Gibt die maximale Größe in Byte für eine Nachricht, die von der Bindung verarbeitet wird. Der Standardwert ist 65.536 Bytes.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert ist kleiner als 0 (null).</exception>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="webHttpRelayBindingElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> Die Bindung, die Einstellungen zu aktualisieren.</param>
        <summary>Wendet die Einstellungen dieses Konfigurationselements auf die angegebene Bindung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft eine Auflistung der Objekte, die Attribute werden können oder Konfiguration Element dieses Konfigurationselements ab.</summary>
        <value>Gibt eine <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> , die eine Auflistung von ConfigurationProperty-Objekte, die Attribute werden können oder ConfigurationElement auf dieses Konfigurationselement enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("proxyAddress", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die URI-Adresse des HTTP-Proxys ab oder legt sie fest.</summary>
        <value>Gibt eine <see cref="T:System.Uri" /> , die als die Adresse des HTTP-Proxy dient. Der Standardwert ist NULL.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("readerQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Konfigurationselement ab, das die Beschränkungen für die Komplexität von SOAP-Meldungen enthält, die von Endpunkten verarbeitet werden können, die mit dieser Bindung konfiguriert wurden, oder legt dieses Element fest.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> , die die Komplexität Einschränkungen enthält.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Die Valueset ist null.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Die Kontingentwerte von XmlDictionaryReaderQuotas sind schreibgeschützt.</exception>
        <exception cref="T:System.ArgumentException">Die festgelegten Kontingente müssen positiv sein.</exception>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WebHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Konfigurationselement ab, das die mit dieser Bindung verwendeten Sicherheitseinstellungen enthält.</summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" /> , das die Sicherheitseinstellungen für diese Bindung enthält. Der Standardwert ist none.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transferMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob der Dienst mit der zugehörigen Bindung Streaming-oder Puffermodus (oder beides) Modi nachrichtenübertragung konfiguriert.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.TransferMode" /> enthält, die angibt, ob der Dienst mit der Bindung verwendet Streaming- oder Puffermodus (oder beides) nachrichtenübertragung. Der Standardwert ist Buffered.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ComponentModel.InvalidEnumArgumentException">Der festgelegte Wert ist kein gültiger Übertragungsmodus Wert.</exception>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("useDefaultWebProxy", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob der automatisch konfigurierte HTTP-Proxy des Systems mit der zugehörigen Bindung verwendet werden soll, falls verfügbar.</summary>
        <value>"true", wenn der automatisch konfigurierte HTTP-Proxy des Systems verwendet, falls verfügbar sein soll; andernfalls "false". Der Standardwert lautet „true“.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding WriteEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding WriteEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.WriteEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.WriteEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.WriteEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.Configuration.EncodingConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("writeEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, das die zeichencodierung, die für den Nachrichtentext in die zugeordnete Bindung verwendet wird.</summary>
        <value>Gibt eine <see cref="T:System.Text.Encoding" /> , der angibt, das die zeichencodierung, die verwendet wird. Der Standardwert ist UTF8Encoding.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Der festgelegte Wert ist null.</exception>
      </Docs>
    </Member>
  </Members>
</Type>