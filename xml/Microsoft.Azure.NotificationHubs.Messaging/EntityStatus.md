<Type Name="EntityStatus" FullName="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus">
  <TypeSignature Language="C#" Value="public enum EntityStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EntityStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum EntityStatus" />
  <TypeSignature Language="F#" Value="type EntityStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="EntityStatus", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="a831e-101">Listet die möglichen Werte für den Status einer messaging-Entität an.</span><span class="sxs-lookup"><span data-stu-id="a831e-101">Enumerates the possible values for the status of a messaging entity.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-102">Der Status der messaging-Entität ist aktiv.</span><span class="sxs-lookup"><span data-stu-id="a831e-102">The status of the messaging entity is active.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus Creating = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 5" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-103">Gibt an, dass die Ressource noch erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="a831e-103">Indicates that the resource is still being created.</span></span> <span data-ttu-id="a831e-104">Jeder Versuch der Erstellung auf dem gleichen Ressourcenpfad führt zu einem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> Ausnahme (HttpCode.Conflict 409).</span><span class="sxs-lookup"><span data-stu-id="a831e-104">Any creation attempt on the same resource path will result in a <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> exception (HttpCode.Conflict 409).</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus Deleting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 6" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-105">Gibt an, dass das System die Bereinigung der Entität weiterhin versucht wird.</span><span class="sxs-lookup"><span data-stu-id="a831e-105">Indicates that the system is still attempting cleanup of the entity.</span></span> <span data-ttu-id="a831e-106">Jeder Aufruf zusätzliche löschen werde (das System benachrichtigt werden).</span><span class="sxs-lookup"><span data-stu-id="a831e-106">Any additional deletion call will be allowed (the system will be notified).</span></span> <span data-ttu-id="a831e-107">Alle zusätzlichen Erstellungsaufruf auf dem gleichen Ressourcenpfad führt zu einem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> Ausnahme (HttpCode.Conflict 409).</span><span class="sxs-lookup"><span data-stu-id="a831e-107">Any additional creation call on the same resource path will result in a <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingException" /> exception (HttpCode.Conflict 409).</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus Disabled = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 1" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-108">Der Status der messaging-Entität ist deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="a831e-108">The status of the messaging entity is disabled.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDisabled">
      <MemberSignature Language="C#" Value="ReceiveDisabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus ReceiveDisabled = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.ReceiveDisabled" />
      <MemberSignature Language="VB.NET" Value="ReceiveDisabled" />
      <MemberSignature Language="F#" Value="ReceiveDisabled = 4" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.ReceiveDisabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-109">Der empfangende Status der messaging-Entität ist deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="a831e-109">The receiving status of the messaging entity is disabled.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Restoring">
      <MemberSignature Language="C#" Value="Restoring" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus Restoring = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Restoring" />
      <MemberSignature Language="VB.NET" Value="Restoring" />
      <MemberSignature Language="F#" Value="Restoring = 2" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.Restoring" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-110">Den vorherigen Status des messaging-Entität wird fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="a831e-110">Resuming the previous status of the messaging entity.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="SendDisabled">
      <MemberSignature Language="C#" Value="SendDisabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.Messaging.EntityStatus SendDisabled = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.SendDisabled" />
      <MemberSignature Language="VB.NET" Value="SendDisabled" />
      <MemberSignature Language="F#" Value="SendDisabled = 3" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityStatus.SendDisabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="a831e-111">Der Status der von der messaging-Entität ist deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="a831e-111">The sending status of the messaging entity is disabled.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>