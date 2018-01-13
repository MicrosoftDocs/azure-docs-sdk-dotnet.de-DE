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
            Definiert die Schnittstelle enthält Methoden, die auf Dienstebene Akteur aufgerufen werden können.
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
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />der Akteur gelöscht werden soll.</param>
        <param name="cancellationToken">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</param>
        <summary>
            Einen Akteur löscht aus dem Akteur-Dienst.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</returns>
        <remarks>
          <para>Akteur active werden deaktiviert, und der Zustand von zustandsanbieter werden ebenfalls gelöscht.</para>
          <para>Ein Status des actorzustands wird von zustandsanbieter gelöscht werden.</para>
          <para>Wenn für eine nicht existierende Akteur-Id in das System Diese Methode aufgerufen wird, kann er nicht ausgeführt werden.</para>
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
        <param name="continuationToken">Ein Fortsetzungstoken, um die Ergebnisse von Abfragen zu starten.
            Ein null-Wert des Fortsetzungstokens bedeutet Zurückgeben von Werten Form Anfang starten.</param>
        <param name="cancellationToken">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</param>
        <summary>
            Ruft die Liste von Akteuren durch Abfragen des Akteur-Diensts ab.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang des Aufrufs an Server darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>