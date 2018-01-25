<Type Name="IActorService" FullName="Microsoft.ServiceFabric.Actors.IActorService">
  <TypeSignature Language="C#" Value="public interface IActorService : Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorService implements class Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.IActorService" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorService&#xA;Implements IService" />
  <TypeSignature Language="F#" Value="type IActorService = interface&#xA;    interface IService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="cacaa-101">Definiert die Schnittstelle enthält Methoden, die auf Dienstebene Akteur aufgerufen werden können.</span><span class="sxs-lookup"><span data-stu-id="cacaa-101">Defines the interface containing methods which can be called at Actor Service level.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteActorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteActorAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorService.DeleteActorAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">
          <span data-ttu-id="cacaa-102"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />der Akteur gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="cacaa-102"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of the actor to be deleted.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cacaa-103">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="cacaa-103">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="cacaa-104">Einen Akteur löscht aus dem Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="cacaa-104">Deletes an Actor from the Actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="cacaa-105">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="cacaa-105">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="cacaa-106">Akteur active werden deaktiviert, und der Zustand von zustandsanbieter werden ebenfalls gelöscht.</span><span class="sxs-lookup"><span data-stu-id="cacaa-106">An active actor, will be deactivated and its state will also be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="cacaa-107">Ein Status des actorzustands wird von zustandsanbieter gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="cacaa-107">An in-active actor's state will be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="cacaa-108">Wenn für eine nicht existierende Akteur-Id in das System Diese Methode aufgerufen wird, kann er nicht ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="cacaa-108">If this method is called for a non-existent actor id in the system, it will be a no-op.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActorsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; GetActorsAsync (Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; GetActorsAsync(class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync(Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetActorsAsync : Microsoft.ServiceFabric.Actors.Query.ContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt;" Usage="iActorService.GetActorsAsync (continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="cacaa-109">Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.</span><span class="sxs-lookup"><span data-stu-id="cacaa-109">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="cacaa-110">Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.</span><span class="sxs-lookup"><span data-stu-id="cacaa-110">A null value of continuation token means start returning values form the beginning.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cacaa-111">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="cacaa-111">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="cacaa-112">Ruft die Liste von Akteuren durch Abfragen des Akteur-Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="cacaa-112">Gets the list of Actors by querying the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="cacaa-113">Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</span><span class="sxs-lookup"><span data-stu-id="cacaa-113">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>