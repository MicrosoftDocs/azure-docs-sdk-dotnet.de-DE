<Type Name="MessageSessionAsyncHandler" FullName="Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler">
  <TypeSignature Language="C#" Value="public abstract class MessageSessionAsyncHandler : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSessionAsyncHandler extends System.Object implements class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSessionAsyncHandler&#xA;Implements IMessageSessionAsyncHandler" />
  <TypeSignature Language="F#" Value="type MessageSessionAsyncHandler = class&#xA;    interface IMessageSessionAsyncHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="46664-101">Stellt die asynchrone Handler, die der meldungssitzung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="46664-101">Represents the asynchronous handler associated with the message session.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MessageSessionAsyncHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.#ctor" />
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
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IMessageSessionAsyncHandler.OnCloseSessionAsync (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.Microsoft#ServiceBus#Messaging#IMessageSessionAsyncHandler#OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Function OnCloseSessionAsync (session As MessageSession) As Task Implements IMessageSessionAsyncHandler.OnCloseSessionAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="46664-102">Die Sitzung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="46664-102">The closed session.</span></span></param>
        <summary><span data-ttu-id="46664-103">Löst ein Ereignis, das auftritt, wenn die Sitzung asynchron geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="46664-103">Raises an event that occurs when the session has been asynchronously closed.</span></span></summary>
        <returns><span data-ttu-id="46664-104">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="46664-104">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IMessageSessionAsyncHandler.OnMessageAsync (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.Microsoft#ServiceBus#Messaging#IMessageSessionAsyncHandler#OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Function OnMessageAsync (session As MessageSession, message As BrokeredMessage) As Task Implements IMessageSessionAsyncHandler.OnMessageAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="46664-105">Die Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="46664-105">The message session.</span></span></param>
        <param name="message"><span data-ttu-id="46664-106">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="46664-106">The brokered message.</span></span></param>
        <summary><span data-ttu-id="46664-107">Stellt ein Ereignis, das auftritt, wenn die Sitzung eine brokernachricht.</span><span class="sxs-lookup"><span data-stu-id="46664-107">Represents an event that occurs when the session has a brokered message.</span></span></summary>
        <returns><span data-ttu-id="46664-108">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="46664-108">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IMessageSessionAsyncHandler.OnSessionLostAsync (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.Microsoft#ServiceBus#Messaging#IMessageSessionAsyncHandler#OnSessionLostAsync(System.Exception)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="46664-109">Die Ausnahme ist aufgetreten, die Sitzung verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="46664-109">The exception occurred that caused the lost session.</span></span></param>
        <summary><span data-ttu-id="46664-110">Löst ein Ereignis, das auftritt, wenn die Sitzung unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="46664-110">Raises an event that occurs when the session has been lost.</span></span></summary>
        <returns><span data-ttu-id="46664-111">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="46664-111">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseSessionAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseSessionAsync (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseSessionAsync(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCloseSessionAsync (session As MessageSession) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseSessionAsync : Microsoft.ServiceBus.Messaging.MessageSession -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseSessionAsync : Microsoft.ServiceBus.Messaging.MessageSession -&gt; System.Threading.Tasks.Task" Usage="messageSessionAsyncHandler.OnCloseSessionAsync session" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnCloseSessionAsync(Microsoft.ServiceBus.Messaging.MessageSession)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="46664-112">Die Sitzung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="46664-112">The closed session.</span></span></param>
        <summary><span data-ttu-id="46664-113">Löst ein Ereignis, das auftritt, wenn die Sitzung asynchron geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="46664-113">Raises an event that occurs when the session has been asynchronously closed.</span></span></summary>
        <returns><span data-ttu-id="46664-114">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="46664-114">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnMessageAsync (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnMessageAsync(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnMessageAsync (session As MessageSession, message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnMessageAsync : Microsoft.ServiceBus.Messaging.MessageSession * Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="messageSessionAsyncHandler.OnMessageAsync (session, message)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnMessageAsync(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session"><span data-ttu-id="46664-115">Die Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="46664-115">The message session.</span></span></param>
        <param name="message"><span data-ttu-id="46664-116">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="46664-116">The brokered message.</span></span></param>
        <summary><span data-ttu-id="46664-117">Stellt ein Ereignis, das auftritt, wenn die Sitzung eine brokernachricht.</span><span class="sxs-lookup"><span data-stu-id="46664-117">Represents an event that occurs when the session has a brokered message.</span></span></summary>
        <returns><span data-ttu-id="46664-118">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="46664-118">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSessionLostAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnSessionLostAsync (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnSessionLostAsync(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)" />
      <MemberSignature Language="F#" Value="abstract member OnSessionLostAsync : Exception -&gt; System.Threading.Tasks.Task&#xA;override this.OnSessionLostAsync : Exception -&gt; System.Threading.Tasks.Task" Usage="messageSessionAsyncHandler.OnSessionLostAsync exception" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandler.OnSessionLostAsync(System.Exception)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="46664-119">Die Ausnahme ist aufgetreten, die Sitzung verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="46664-119">The exception occurred that caused the lost session.</span></span></param>
        <summary><span data-ttu-id="46664-120">Löst ein Ereignis, das auftritt, wenn die Sitzung unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="46664-120">Raises an event that occurs when the session has been lost.</span></span></summary>
        <returns><span data-ttu-id="46664-121">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="46664-121">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>