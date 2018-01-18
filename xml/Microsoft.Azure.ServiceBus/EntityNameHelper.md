<Type Name="EntityNameHelper" FullName="Microsoft.Azure.ServiceBus.EntityNameHelper">
  <TypeSignature Language="C#" Value="public static class EntityNameHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EntityNameHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.EntityNameHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class EntityNameHelper" />
  <TypeSignature Language="F#" Value="type EntityNameHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2af9d-101">Diese Klasse kann verwendet werden, um den Pfad für verschiedene Typen von Service Bus-Entität zu formatieren.</span><span class="sxs-lookup"><span data-stu-id="2af9d-101">This class can be used to format the path for different Service Bus entity types.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (entityPath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string -&gt; string" Usage="Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="2af9d-102">Der Name der Warteschlange oder Pfad des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2af9d-102">The name of the queue, or path of the subscription.</span></span></param>
        <summary>
            <span data-ttu-id="2af9d-103">Formatiert den unzustellbare Pfad für eine Warteschlange oder ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="2af9d-103">Formats the dead letter path for either a queue, or a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="2af9d-104">Der Pfad als Zeichenfolge an die Dead Letter-Entität.</span><span class="sxs-lookup"><span data-stu-id="2af9d-104">The path as a string of the dead letter entity.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatSubQueuePath">
      <MemberSignature Language="C#" Value="public static string FormatSubQueuePath (string entityPath, string subQueueName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatSubQueuePath(string entityPath, string subQueueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubQueuePath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatSubQueuePath (entityPath As String, subQueueName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatSubQueuePath : string * string -&gt; string" Usage="Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubQueuePath (entityPath, subQueueName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="subQueueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="2af9d-105">Der Name der Warteschlange oder Pfad des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2af9d-105">The name of the queue, or path of the subscription.</span></span></param>
        <param name="subQueueName"><span data-ttu-id="2af9d-106">Der Name der Unterwarteschlange.</span><span class="sxs-lookup"><span data-stu-id="2af9d-106">The name of the subqueue.</span></span></param>
        <summary>
            <span data-ttu-id="2af9d-107">Formatiert den Pfad in die Unterwarteschlange für eine Warteschlange oder ein Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="2af9d-107">Formats the subqueue path for either a queue, or a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="2af9d-108">Der Pfad als Zeichenfolge bestehend aus der Unterwarteschlange-Entität.</span><span class="sxs-lookup"><span data-stu-id="2af9d-108">The path as a string of the subqueue entity.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatSubscriptionPath">
      <MemberSignature Language="C#" Value="public static string FormatSubscriptionPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatSubscriptionPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatSubscriptionPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatSubscriptionPath : string * string -&gt; string" Usage="Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="2af9d-109">Der Name des Themas, einschließlich Schrägstriche.</span><span class="sxs-lookup"><span data-stu-id="2af9d-109">The name of the topic, including slashes.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="2af9d-110">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="2af9d-110">The name of the subscription.</span></span></param>
        <summary>
            <span data-ttu-id="2af9d-111">Formatiert die Abonnement-Pfad, basierend auf dem Thema Berichtspfad und die Abonnement-Namen an.</span><span class="sxs-lookup"><span data-stu-id="2af9d-111">Formats the subscription path, based on the topic path and subscription name.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (entityPath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.Azure.ServiceBus.EntityNameHelper.FormatTransferDeadLetterPath entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">To be added.</param>
        <summary>
            <span data-ttu-id="2af9d-112">Utility-Methode, die den Namen für die Übertragung unzustellbare Empfänger gemäß erstellt<paramref name="entityPath" /></span><span class="sxs-lookup"><span data-stu-id="2af9d-112">Utility method that creates the name for the transfer dead letter receiver, specified by <paramref name="entityPath" /></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>