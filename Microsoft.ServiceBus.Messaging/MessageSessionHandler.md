<Type Name="MessageSessionHandler" FullName="Microsoft.ServiceBus.Messaging.MessageSessionHandler">
  <TypeSignature Language="C#" Value="public abstract class MessageSessionHandler : Microsoft.ServiceBus.Messaging.IMessageSessionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSessionHandler extends System.Object implements class Microsoft.ServiceBus.Messaging.IMessageSessionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSessionHandler" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSessionHandler&#xA;Implements IMessageSessionHandler" />
  <TypeSignature Language="F#" Value="type MessageSessionHandler = class&#xA;    interface IMessageSessionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceBus.Messaging.IMessageSessionHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="c2fb3-101">Stellt den Ereignishandler der meldungssitzung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-101">Represents the handler associated with the message session.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MessageSessionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
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
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnCloseSession">
      <MemberSignature Language="C#" Value="void IMessageSessionHandler.OnCloseSession (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnCloseSession(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.Microsoft#ServiceBus#Messaging#IMessageSessionHandler#OnCloseSession(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Sub OnCloseSession (session As MessageSession) Implements IMessageSessionHandler.OnCloseSession" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnCloseSession(Microsoft.ServiceBus.Messaging.MessageSession)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="c2fb3-102">Die Sitzung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-102">The closed session.</span></span></param>
        <summary><span data-ttu-id="c2fb3-103">Löst ein Ereignis, das auftritt, wenn die Sitzung geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-103">Raises an event that occurs when the session has been closed.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnMessage">
      <MemberSignature Language="C#" Value="void IMessageSessionHandler.OnMessage (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnMessage(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.Microsoft#ServiceBus#Messaging#IMessageSessionHandler#OnMessage(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Sub OnMessage (session As MessageSession, message As BrokeredMessage) Implements IMessageSessionHandler.OnMessage" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnMessage(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="c2fb3-104">Die Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-104">The message session.</span></span></param>
        <param name="message"><span data-ttu-id="c2fb3-105">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-105">The brokered message.</span></span></param>
        <summary><span data-ttu-id="c2fb3-106">Stellt ein Ereignis, das auftritt, wenn die Sitzung eine brokernachricht.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-106">Represents an event that occurs when the session has a brokered message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnSessionLost">
      <MemberSignature Language="C#" Value="void IMessageSessionHandler.OnSessionLost (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnSessionLost(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.Microsoft#ServiceBus#Messaging#IMessageSessionHandler#OnSessionLost(System.Exception)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnSessionLost(System.Exception)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="c2fb3-107">Die Ausnahme ist aufgetreten, die Sitzung verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-107">The exception occurred that caused the lost session.</span></span></param>
        <summary><span data-ttu-id="c2fb3-108">Löst ein Ereignis, das auftritt, wenn die Sitzung unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-108">Raises an event that occurs when the session has been lost.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseSession">
      <MemberSignature Language="C#" Value="protected virtual void OnCloseSession (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnCloseSession(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.OnCloseSession(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnCloseSession (session As MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseSession : Microsoft.ServiceBus.Messaging.MessageSession -&gt; unit&#xA;override this.OnCloseSession : Microsoft.ServiceBus.Messaging.MessageSession -&gt; unit" Usage="messageSessionHandler.OnCloseSession session" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnCloseSession(Microsoft.ServiceBus.Messaging.MessageSession)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="c2fb3-109">Die Sitzung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-109">The closed session.</span></span></param>
        <summary><span data-ttu-id="c2fb3-110">Löst ein Ereignis, das auftritt, wenn die Sitzung geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-110">Raises an event that occurs when the session has been closed.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="protected abstract void OnMessage (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnMessage(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.OnMessage(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnMessage (session As MessageSession, message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member OnMessage : Microsoft.ServiceBus.Messaging.MessageSession * Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="messageSessionHandler.OnMessage (session, message)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnMessage(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="c2fb3-111">Die Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-111">The message session.</span></span></param>
        <param name="message"><span data-ttu-id="c2fb3-112">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-112">The brokered message.</span></span></param>
        <summary><span data-ttu-id="c2fb3-113">Stellt ein Ereignis, das auftritt, wenn die Sitzung eine brokernachricht.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-113">Represents an event that occurs when the session has a brokered message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSessionLost">
      <MemberSignature Language="C#" Value="protected virtual void OnSessionLost (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSessionLost(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionHandler.OnSessionLost(System.Exception)" />
      <MemberSignature Language="F#" Value="abstract member OnSessionLost : Exception -&gt; unit&#xA;override this.OnSessionLost : Exception -&gt; unit" Usage="messageSessionHandler.OnSessionLost exception" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnSessionLost(System.Exception)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="c2fb3-114">Die Ausnahme ist aufgetreten, die Sitzung verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-114">The exception occurred that caused the lost session.</span></span></param>
        <summary><span data-ttu-id="c2fb3-115">Löst ein Ereignis, das auftritt, wenn die Sitzung unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="c2fb3-115">Raises an event that occurs when the session has been lost.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>