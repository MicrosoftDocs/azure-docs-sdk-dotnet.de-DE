<Type Name="WSHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingElement : Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingElement extends Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingElement&#xA;Inherits WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingElement = class&#xA;    inherit WSHttpRelayBindingBaseElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Konfigurationselement, das eine interoperable Bindung darstellt, die verteilte Transaktionen und sichere, zuverlässige Sitzungen unterstützt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.AllowCookies" />
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
        <summary>Ruft ab oder legt einen Wert, der angibt, ob der Dienst oder Client Cookies akzeptiert und für zukünftige Anfragen propagiert.</summary>
        <value>"true", wenn der Dienst oder Client Cookies akzeptiert und für zukünftige Anfragen propagiert; andernfalls "false". Der Standardwert ist false.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Typ des der <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</summary>
        <value>Der Typ des der <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> Die Bindung zum Initialisieren dieses Konfigurationselements aus.</param>
        <summary>Initialisiert dieses bindungskonfigurationselement mit dem Inhalt der angegebenen Bindung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingElement.OnApplyConfiguration binding" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft eine Auflistung von Eigenschaften für dieses bindungskonfigurationselement.</summary>
        <value>Eine Auflistung von Eigenschaften für dieses bindungskonfigurationselement.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WSHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Security" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> Konfigurationselement, die Sicherheitseinstellungen für enthält, die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</summary>
        <value>Die <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> Konfigurationselement, die Sicherheitseinstellungen für enthält, die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>