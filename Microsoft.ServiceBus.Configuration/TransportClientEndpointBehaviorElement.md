<Type Name="TransportClientEndpointBehaviorElement" FullName="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement">
  <TypeSignature Language="C#" Value="public class TransportClientEndpointBehaviorElement : System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransportClientEndpointBehaviorElement extends System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TransportClientEndpointBehaviorElement&#xA;Inherits BehaviorExtensionElement" />
  <TypeSignature Language="F#" Value="type TransportClientEndpointBehaviorElement = class&#xA;    inherit BehaviorExtensionElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.BehaviorExtensionElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt ein Konfigurationselement, das Verhalten eines Dienst- oder Client-Endpunkts für einen Transport für die Azure Service Bus-Relay angibt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehaviorElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.#ctor" />
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
    <Member MemberName="BehaviorType">
      <MemberSignature Language="C#" Value="public override Type BehaviorType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BehaviorType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.BehaviorType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BehaviorType As Type" />
      <MemberSignature Language="F#" Value="member this.BehaviorType : Type" Usage="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.BehaviorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, oder legt ihn fest das Verhalten für den Clientendpunkt Transport.</summary>
        <value>Der Verhaltenstyp für den Clientendpunkt Transport.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="transportClientEndpointBehaviorElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"> Das Konfigurationselement zum Kopieren der Inhalte aus.</param>
        <summary>Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBehavior">
      <MemberSignature Language="C#" Value="protected override object CreateBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object CreateBehavior() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.CreateBehavior" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateBehavior () As Object" />
      <MemberSignature Language="F#" Value="override this.CreateBehavior : unit -&gt; obj" Usage="transportClientEndpointBehaviorElement.CreateBehavior " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt eine neue <see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> Objekt mit den gleichen Einstellungen wie dieses Konfigurationselement.</summary>
        <returns>Ein neues <see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> Objekt mit den gleichen Einstellungen wie dieses Konfigurationselement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Auflistung der in diesem Konfigurationselement enthaltenen Eigenschaften ab.</summary>
        <value>Die Auflistung der in diesem Konfigurationselement enthaltenen Eigenschaften.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.TokenProviderElement TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.TokenProviderElement TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProviderElement" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.ServiceBus.Configuration.TokenProviderElement" Usage="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.TokenProviderElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Tokenanbieter, der als Bindungsparameter verwendet wird.</summary>
        <value>Der Tokenanbieter, der als Bindungsparameter verwendet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>