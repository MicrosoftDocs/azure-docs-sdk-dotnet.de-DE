<Type Name="TransportClientEndpointBehaviorElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement">
  <TypeSignature Language="C#" Value="public class TransportClientEndpointBehaviorElement : System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransportClientEndpointBehaviorElement extends System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TransportClientEndpointBehaviorElement&#xA;Inherits BehaviorExtensionElement" />
  <TypeSignature Language="F#" Value="type TransportClientEndpointBehaviorElement = class&#xA;    inherit BehaviorExtensionElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.BehaviorExtensionElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d7cf5-101">Stellt ein Konfigurationselement, das das Verhalten eines Dienst- oder Client-Endpunkts für einen Transport gibt an, auf dem Windows Azure Service Bus-Relay dar.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-101">Represents a configuration element that specifies the behavior of a service or client endpoint for a transport on the Windows Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehaviorElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d7cf5-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BehaviorType">
      <MemberSignature Language="C#" Value="public override Type BehaviorType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BehaviorType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.BehaviorType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BehaviorType As Type" />
      <MemberSignature Language="F#" Value="member this.BehaviorType : Type" Usage="Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.BehaviorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d7cf5-103">Ruft ab, oder legt ihn fest das Verhalten für den Clientendpunkt Transport.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-103">Gets or sets the behavior type for the transport client endpoint.</span></span></summary>
        <value><span data-ttu-id="d7cf5-104">Der Verhaltenstyp für den Clientendpunkt Transport.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-104">The behavior type for the transport client endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="transportClientEndpointBehaviorElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"><span data-ttu-id="d7cf5-105">Das Konfigurationselement zum Kopieren der Inhalte aus.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-105">The configuration element to copy the contents from.</span></span></param>
        <summary><span data-ttu-id="d7cf5-106">Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-106">Copies the contents of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBehavior">
      <MemberSignature Language="C#" Value="protected override object CreateBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object CreateBehavior() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.CreateBehavior" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateBehavior () As Object" />
      <MemberSignature Language="F#" Value="override this.CreateBehavior : unit -&gt; obj" Usage="transportClientEndpointBehaviorElement.CreateBehavior " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d7cf5-107">Gibt eine neue <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" /> Objekt mit den gleichen Einstellungen wie dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-107">Returns a new <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" /> object with the same settings as this configuration element.</span></span></summary>
        <returns><span data-ttu-id="d7cf5-108">Ein neues <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" /> Objekt mit den gleichen Einstellungen wie dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-108">A new <see cref="T:Microsoft.Azure.NotificationHubs.TransportClientEndpointBehavior" /> object with the same settings as this configuration element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d7cf5-109">Ruft die Auflistung der in diesem Konfigurationselement enthaltenen Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-109">Gets the collection of properties contained in this configuration element.</span></span></summary>
        <value><span data-ttu-id="d7cf5-110">Die Auflistung der in diesem Konfigurationselement enthaltenen Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-110">The collection of properties contained in this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProviderElement" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement" Usage="Microsoft.Azure.NotificationHubs.Configuration.TransportClientEndpointBehaviorElement.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d7cf5-111">Ruft ab oder legt den Tokenanbieter, der als Bindungsparameter verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-111">Gets or sets the token provider that is used as a binding parameter.</span></span></summary>
        <value><span data-ttu-id="d7cf5-112">Der Tokenanbieter, der als Bindungsparameter verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="d7cf5-112">The token provider used as a binding parameter.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>