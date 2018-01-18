<Type Name="IMobileServiceSyncHandler" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncHandler" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ddbe1-101">Fehler bei Vorgängen Handles Tabelle und Push Abschluss Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-101">Handles table operation errors and push completion results.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExecuteTableOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; ExecuteTableOperationAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; ExecuteTableOperationAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler.ExecuteTableOperationAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteTableOperationAsync (operation As IMobileServiceTableOperation) As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteTableOperationAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceSyncHandler.ExecuteTableOperationAsync operation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="ddbe1-102">Instanz des <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation" /> , der einen Remotetabelle Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-102">Instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation" /> that represents a remote table operation.</span></span></param>
        <summary>
            <span data-ttu-id="ddbe1-103">Eine Methode, die aufgerufen wird, um einen einzelnen tabellenvorgang gegen Remotetabelle auszuführen.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-103">A method that is called to execute a single table operation against remote table.</span></span>
            </summary>
        <returns><span data-ttu-id="ddbe1-104">Eine Aufgabe, die die Server-Version des Elements zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-104">Task that returns the server version of the item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPushCompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OnPushCompleteAsync (Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OnPushCompleteAsync(class Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler.OnPushCompleteAsync(Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function OnPushCompleteAsync (result As MobileServicePushCompletionResult) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnPushCompleteAsync : Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncHandler.OnPushCompleteAsync result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ddbe1-105">Eine Instanz von <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" />.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-105">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServicePushCompletionResult" /></span></span></param>
        <summary>
            <span data-ttu-id="ddbe1-106">Eine Methode, die aufgerufen wird, wenn die Push-Vorgang abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-106">A method that is called when push operation has completed.</span></span>
            </summary>
        <returns><span data-ttu-id="ddbe1-107">Eine Aufgabe, die abgeschlossen wird, wenn das Ergebnis verarbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="ddbe1-107">Task that completes when result has been handled.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>