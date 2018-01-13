<Type Name="NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public abstract class NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt; : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NotifyDictionaryChangedEventArgs`2&lt;TKey, TValue&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NotifyDictionaryChangedEventArgs(Of TKey, TValue)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey"><span data-ttu-id="bffd3-101">Der Typ der Schlüssel in der <cref name="IReliableDictionary" />.</span><span class="sxs-lookup"><span data-stu-id="bffd3-101">The type of the keys in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="bffd3-102">Der Typ der Werte in der <cref name="IReliableDictionary" />.</span><span class="sxs-lookup"><span data-stu-id="bffd3-102">The type of the values in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="bffd3-103">Stellt Daten für das DictionaryChanged-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="bffd3-103">Provides data for the DictionaryChanged event.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="bffd3-104">DictionaryChanged Benachrichtigungen werden durch synchron ausgelöst <cref name="IReliableDictionary" /> als Teil der Anwendung des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bffd3-104">DictionaryChanged notifications are synchronously fired by <cref name="IReliableDictionary" /> as part of applying the operation.</span></span>
            <span data-ttu-id="bffd3-105">Aufhält auf den Abschluss dieser Ereignisse kann dazu führen, dass das Replikat auf den Abschluss des Ereignisses blockiert wird.</span><span class="sxs-lookup"><span data-stu-id="bffd3-105">Holding up the completion of these events can cause the replica to be blocked on the completion of the event.</span></span>
            <span data-ttu-id="bffd3-106">Es wird empfohlen, dass die Ereignisse so schnell wie möglich behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="bffd3-106">It is recommended that the events are handled as fast as possible.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryChangedEventArgs (Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As NotifyDictionaryChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; action" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" />
      </Parameters>
      <Docs>
        <param name="action"><span data-ttu-id="bffd3-107">Der Typ der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="bffd3-107">The type of notification.</span></span></param>
        <summary>
            <span data-ttu-id="bffd3-108">Initialisiert eine neue Instanz der dem<cref name="NotifyDictionaryChangedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="bffd3-108">Initializes a new instance of the <cref name="NotifyDictionaryChangedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As NotifyDictionaryChangedAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bffd3-109">Ruft die Aktion ab, die das Ereignis verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="bffd3-109">Gets the action that caused the event.</span></span>
            </summary>
        <value><span data-ttu-id="bffd3-110">Der Typ der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="bffd3-110">The type of notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>