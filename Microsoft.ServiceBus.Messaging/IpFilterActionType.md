<Type Name="IpFilterActionType" FullName="Microsoft.ServiceBus.Messaging.IpFilterActionType">
  <TypeSignature Language="C#" Value="public enum IpFilterActionType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IpFilterActionType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IpFilterActionType" />
  <TypeSignature Language="VB.NET" Value="Public Enum IpFilterActionType" />
  <TypeSignature Language="F#" Value="type IpFilterActionType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="IpFilterActionType", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Darstellen von den Typ der Aktion, die IP-Adresse, die die IpFilter entsprechen angewendet wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Accept">
      <MemberSignature Language="C#" Value="Accept" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.IpFilterActionType Accept = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.IpFilterActionType.Accept" />
      <MemberSignature Language="VB.NET" Value="Accept" />
      <MemberSignature Language="F#" Value="Accept = 1" Usage="Microsoft.ServiceBus.Messaging.IpFilterActionType.Accept" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IpFilterActionType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Wenn eine IP-Adresse übereinstimmt, wird die Verbindung zugelassen.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Reject">
      <MemberSignature Language="C#" Value="Reject" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.IpFilterActionType Reject = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.IpFilterActionType.Reject" />
      <MemberSignature Language="VB.NET" Value="Reject" />
      <MemberSignature Language="F#" Value="Reject = 0" Usage="Microsoft.ServiceBus.Messaging.IpFilterActionType.Reject" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IpFilterActionType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Wenn eine IP-Adresse übereinstimmt, wird die IP-Adresse eine Verbindung mit dem Dienst abgelehnt.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>