<Type Name="EntityDescription" FullName="Microsoft.ServiceBus.Messaging.EntityDescription">
  <TypeSignature Language="C#" Value="public abstract class EntityDescription : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityDescription extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityDescription&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type EntityDescription = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.QueueDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.TopicDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.SubscriptionDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.RuleDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.EventHubDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.PartitionDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.RevokedPublisherDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.RelayDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Relay.HybridConnectionDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt die Beschreibung einer Entität.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EntityDescription.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.ServiceBus.Messaging.EntityDescription.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Struktur ab, die zusätzliche Daten enthält, oder legt diese fest.</summary>
        <value>Ein <see cref="T:System.Runtime.Serialization.ExtensionDataObject" />, der Daten enthält, die nicht als zum Datenvertrag gehörend erkannt werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EntityDescription.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.ServiceBus.Messaging.EntityDescription.IsReadOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die entitätsbeschreibung schreibgeschützt ist.</summary>
        <value>"true", wenn die entitätsbeschreibung schreibgeschützt ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfReadOnly">
      <MemberSignature Language="C#" Value="protected void ThrowIfReadOnly ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfReadOnly() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EntityDescription.ThrowIfReadOnly" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfReadOnly ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfReadOnly : unit -&gt; unit" Usage="entityDescription.ThrowIfReadOnly " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Löst eine Ausnahme aus, wenn die entitätsbeschreibung schreibgeschützt ist.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>