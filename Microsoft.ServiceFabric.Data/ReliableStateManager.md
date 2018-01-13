<Type Name="ReliableStateManager" FullName="Microsoft.ServiceFabric.Data.ReliableStateManager">
  <TypeSignature Language="C#" Value="public class ReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;, Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ReliableStateManager extends System.Object implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;, class Microsoft.ServiceFabric.Data.IReliableStateManager, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState), IReliableStateManagerReplica2" />
  <TypeSignature Language="F#" Value="type ReliableStateManager = class&#xA;    interface IReliableStateManagerReplica2&#xA;    interface IReliableStateManagerReplica&#xA;    interface IStateProviderReplica&#xA;    interface IReliableStateManager&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;&#xA;    interface IStateProviderReplica2" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            Die ReliableStateManager-Klasse ist verantwortlich für die Verwaltung von <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> für ein Replikat des Diensts.
            Jedes Replikat in einem Dienst hat seinen eigenen <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> und <see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />. 
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />zählen <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />, <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />, oder eine beliebige <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> Typen.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManager (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceContext As StatefulServiceContext, Optional configuration As ReliableStateManagerConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ReliableStateManager : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration -&gt; Microsoft.ServiceFabric.Data.ReliableStateManager" Usage="new Microsoft.ServiceFabric.Data.ReliableStateManager (serviceContext, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="configuration" Type="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" />
      </Parameters>
      <Docs>
        <param name="serviceContext">Ein <see cref="T:System.Fabric.StatefulServiceContext" /> , beschreibt der Kontext.</param>
        <param name="configuration">Konfigurationsparameter.</param>
        <summary>
            Erstellen Sie eine neue ReliableStateManager.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync backupCallback" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</param>
        <summary>
            Führt eine vollständige Sicherung alle zuverlässigen Zustand, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Eine vollständige Sicherung wird mit einem Timeout einer Stunde ausgeführt.
            Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.
            Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.
            Darüber hinaus wird Sicherung als fehlgeschlagen markiert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync (option, timeout, cancellationToken, backupCallback)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option">Der Typ der Sicherung ausführen.</param>
        <param name="timeout">Das Timeout für diesen Vorgang.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <param name="backupCallback">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</param>
        <summary>
            Führt eine Sicherung alle zuverlässige Status, die von diesem verwaltet <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.
            Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.
            Darüber hinaus wird Sicherung als fehlgeschlagen markiert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsyncEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.IAsyncEnumerator`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.GetAsyncEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAsyncEnumerator () As IAsyncEnumerator(Of IReliableState)" />
      <MemberSignature Language="F#" Value="abstract member GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;&#xA;override this.GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" Usage="reliableStateManager.GetAsyncEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt einen Enumerator zurück, der die Auflistung durchläuft.
            </summary>
        <returns>
            Ein <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" />-Objekt, das zum Durchlaufen der Auflistung verwendet werden kann.
            </returns>
        <remarks>To be added.</remarks>
        <filterpriority>1</filterpriority>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction">
      <MemberSignature Language="C#" Value="Microsoft.ServiceFabric.Data.ITransaction IReliableStateManager.CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Function CreateTransaction () As ITransaction Implements IReliableStateManager.CreateTransaction" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellen Sie und starten Sie eine neue Transaktion, die zum Gruppieren von Operationen verwendet werden kann, um atomar ausgeführt werden.
            </summary>
        <returns>Eine neue Transaktion.</returns>
        <remarks>
            Vorgänge werden für die Transaktion hinzugefügt, durch das Übergeben der <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> -Objekt in zuverlässigen Zustand Methoden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Beim Angeben der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typ Sie Fragen sich vielleicht für einen Klassentyp oder einen Schnittstellentyp aufweisen.
            <para>Wenn Sie einen Klassentyp angeben, wird versucht, eine Instanz dieses Typs zurückzugeben. Wenn eine Instanz dieses Typs instanziiert werden kann (z. B. abstrakte Klasse, es ist kein geeigneter Konstruktor) ArgumentException ausgelöst wird. </para><para>Wenn Sie einen Schnittstellentyp angeben, versucht der Manager die Schnittstelle in einen konkreten Typ aufgelöst. Wenn Typzuordnung vom Benutzer angegeben wird, wird diese Methode die benutzerdefinierte Zuordnung verwenden, um den Typ (noch nicht unterstützt) aufzulösen. Wenn die Typzuordnung nicht angegeben wird, wird der Benutzer wählt diese Methode die standardmäßige Implementierung für die angegebene Schnittstelle. Wenn Sie der angegebenen Schnittstellentyp verfügt nicht über eine Standardimplementierung oder eine benutzerdefinierte Zuordnung für den Typ nicht angegeben ist, oder der Typ ist ungültig, löst diese Methode ArgumentException.</para></typeparam>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen, wenn es vorhanden ist, oder erstellt und wird zurückgegeben, wenn er nicht bereits vorhanden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist die zuverlässige Status-Instanz.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Wenn ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> muss erstellt werden, wird entweder abgeschlossen und erfolgreich abgeschlossen oder er wird nicht erstellt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Eine Instanz des Typs <typeparamref name="T" /> kann nicht erstellt werden, oder die vorhandene <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht vom Typ <typeparamref name="T" />, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Status wird dauerhaft aus dem persistenten Speicher und alle Replikate entfernt.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="name">Der Name des zu entfernenden <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <summary>
            Entfernt die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen aus diesem Status-Manager. Der Zustand ist endgültig aus dem persistenten Speicher und alle Replikate entfernt, wenn die Transaktion ein Commit ausgeführt wird.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</returns>
        <remarks>
            Dies ist einer atomaren Operation. Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> in intakt gelassen werden oder wird zusammen mit allen Zustand erfolgreich entfernt werden. Wenn diese Methode eine Ausnahme auslöst, muss die Transaktion abgebrochen.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="name" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> mit dem angegebenen Namen ist nicht vorhanden, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Z. B. für die Transaktion verwendet bereits beendet: löschen oder zusichern.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="bool IReliableStateManager.TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean Implements IReliableStateManager.TryAddStateSerializer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateSerializer" Type="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">Typ, der serialisiert und deserialisiert werden.</typeparam>
        <param name="stateSerializer">
            Das Serialisierungsprogramm Zustand hinzugefügt werden.
            </param>
        <summary>
            Fügt eine Status-Serialisierer hinzu.
            Wird für alle Instanzen von zuverlässigen Auflistung hinzugefügt.
            </summary>
        <returns>
            "True", wenn das Serialisierungsprogramm hinzugefügt wurde.
            "False", wenn eine Serailizer bereits registriert ist.
            </returns>
        <remarks>
            Diese Methode kann nur in InitializeStateSerializers aufgerufen werden.
            Instanz bestimmten Zustand Serialisierungsprogramme haben immer Vorrang vor.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Wenn Sie den Typ angeben, können Sie einen konkreten Typ oder einen Schnittstellentyp anfordern. Das abgerufene Objekt wird für den angegebenen Typ umgewandelt werden.
            </typeparam>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <summary>
            Versucht, erhalten eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, die angibt, ob die zuverlässige Zustand gefunden wurde, und wenn dies der Fall ist die Instanz.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht in den Typ <typeparamref name="T" />.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass der Status-Manager abrufen eine zuverlässige Auflistung kann nicht.
            <see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Beispielsweise, wenn eine <see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> verliert <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            Wenn Sie den Typ angeben, können Sie einen konkreten Typ oder einen Schnittstellentyp anfordern. Das abgerufene Objekt wird für den angegebenen Typ umgewandelt werden.
            </typeparam>
        <param name="name">
            Der Name des <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />. Dieser Name muss in diesem eindeutig sein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> über <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Typen, einschließlich der nicht verknüpfte Typen.
            </param>
        <summary>
            Versucht, erhalten eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> des angegebenen Typs <typeparamref name="T" /> und mit dem angegebenen Namen.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, die angibt, ob die zuverlässige Zustand gefunden wurde, und wenn dies der Fall ist die Instanz.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Instanz ist nicht in den Typ <typeparamref name="T" />.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass der Status-Manager abrufen eine zuverlässige Auflistung kann nicht.
            <see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Beispielsweise, wenn eine <see cref="F:System.Fabric.ReplicaRole.Primary" /> oder <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> verliert <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Bricht einen Zustand Anbieter Replikat erzwungen ab.
            </summary>
        <remarks>
            Dies tritt normalerweise auf, wenn auf dem Knoten ein dauerhafter Fehler erkannt wird oder wenn das Replikat Lifecycle aufgrund von internen Fehlern von Service Fabric zuverlässig verwalten kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">Die neue replikatrolle, z. B. Primary oder Secondary sein.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Dem State-Anbieter-Replikat zu benachrichtigen, dass seine Rolle geändert hat, z. B. um Primary oder Secondary sein.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Rolle Änderungsvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Geschlossen Sie das Replikat der State-Anbieter ordnungsgemäß werden.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Dies tritt normalerweise auf, wenn das Replikat Code ein Upgrade wird, das Replikat aufgrund des Lastenausgleichs verschoben wird oder ein vorübergehender Fehler erkannt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">Initialisierungsinformationen für Dienst z. B. Dienstnamen, Partitions-Id, Replikat-Id und Code-Paketinformationen.</param>
        <summary>
            Das Status Anbieter Replikat unter Verwendung des Diensts Initialisierung zu initialisieren.
            </summary>
        <remarks>
            Keine komplexen Verarbeitung sollte bei der Initialisierung erfolgen. Teuer oder lang ausgeführte Initialisierung sollte im OpenAsync erfolgen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">Gibt an, ob es sich um ein neues oder vorhandenes Replikat handelt.</param>
        <param name="partition">Die Partition dieses Replikat gehört.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Öffnen Sie das Replikat des Status-Anbieter für die Verwendung an.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Öffnungsvorgang darstellt. Das Ergebnis enthält Replikator für die Replikation des Status zwischen Replikaten Anbieter Status in der Partition verantwortlich.
            </returns>
        <remarks>
            Erweiterte Status anbieterinitialisierung, die Aufgaben zu diesem Zeitpunkt gestartet werden können.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Legen Sie diese Eigenschaft, um Benachrichtigungen zu Wenn dies <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> vermutet Daten verloren gehen.
            </summary>
        <value>
            Funktion, die als Teil der Verarbeitung von mutmaßlicher Verlust aufgerufen.
            </value>
        <remarks>
          <para>
            OnDataLossAsync Funktion nimmt CancellationToken und muss eine Aufgabe zurückgeben, die die asynchrone Verarbeitung des Ereignisses darstellt.
            Rückgabe "true" gibt an, dass die zuverlässige Status-Manager-Zustand wiederhergestellt wurde.
            Rückgabe "false" gibt an, dass die zuverlässige Status-Manager-Zustand nicht geändert wurde.
            </para>
          <para>
            Der übergebene Delegat sollte das angegebene Abbruchtoken, das auf abbruchanforderungen überwachen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Funktion mit dem Namen nach Wiederherstellung wurde auf dem Replikat ausgeführt.
            </summary>
        <value>
            Funktion wird aufgerufen, wenn der Status des Replikats durch das Framework erfolgreich wiederhergestellt wurde
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupFolderPath As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync backupFolderPath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <summary>
            Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>
            Eine sichere Sicherung wird ausgeführt werden, was bedeutet, dass die Wiederherstellung wird nur ausgeführt wird, wenn Sie die Daten zum Wiederherstellen nach Status, der das aktuelle Replikat ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync (backupFolderPath, restorePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <param name="restorePolicy">Die Richtlinie für die Wiederherstellung.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Wiederherstellen eine Sicherung von <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> oder <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Status-Manager geändert wird.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn eine Transaktion ändert.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
  </Members>
</Type>