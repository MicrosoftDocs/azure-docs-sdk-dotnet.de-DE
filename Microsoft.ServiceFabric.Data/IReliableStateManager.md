<Type Name="IReliableStateManager" FullName="Microsoft.ServiceFabric.Data.IReliableStateManager">
  <TypeSignature Language="C#" Value="public interface IReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableStateManager implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState)" />
  <TypeSignature Language="F#" Value="type IReliableStateManager = interface&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Verwaltet alle <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> für ein Replikat des Diensts.
            Jedes Replikat in einem Dienst verfügt über einen eigenen Status-Manager, und daher einen eigenen Satz von <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As ITransaction" />
      <MemberSignature Language="F#" Value="abstract member CreateTransaction : unit -&gt; Microsoft.ServiceFabric.Data.ITransaction" Usage="iReliableStateManager.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass die zuverlässige Status-Manager geschlossen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn Status-Manager Zustand ändert.
            Beispielsweise erstellen oder Löschen von zuverlässigen Zustand oder Neuerstellung des zuverlässigen Status-Managers.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn eine Transaktion Zustand ändert.
            Beispielsweise ein Commit einer Transaktion ausgeführt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="public bool TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateSerializer : Microsoft.ServiceFabric.Data.IStateSerializer&lt;'T&gt; -&gt; bool" Usage="iReliableStateManager.TryAddStateSerializer stateSerializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <typeparam name="T">Typ, der serialisiert bzw. deserialisiert werden.</typeparam>
        <param name="stateSerializer">
            Das Serialisierungsprogramm Zustand hinzugefügt werden.
            </param>
        <summary>
            Registriert ein benutzerdefiniertes Serialisierungsprogramm für alle zuverlässige Auflistungen.
            </summary>
        <returns>
            "True", wenn das benutzerdefinierte Serialisierungsprogramm hinzugefügt wurde.
            "False", wenn ein benutzerdefiniertes Serialisierungsprogramm für den angegebenen Typ ist bereits vorhanden.
            </returns>
        <remarks>
          <para>
            Wenn eine zuverlässige Auflistung ein Objekt zu serialisieren muss, fordert er den Status-Manager für ein Serialisierungsprogramm für den angegebenen Typ.
            Der Status-Manager prüft zunächst, wenn es ein benutzerdefiniertes Serialisierungsprogramm für den Eingabetyp registriert ist. Ist dies nicht der Fall, wird überprüft, ob eines der integrierten Serialisierungsprogramme den Typ serialisieren kann. Der Status-Manager verfügt über integrierte Serialisierungsprogrammen für die folgenden Typen: Guid, Bool, Byte, Sbyte, Char, Decimal, double, Float, Int, Uint, long, Ulong, Short, Ushort und Zeichenfolge. Falls nicht, er verwendet <see cref="T:System.Runtime.Serialization.DataContractSerializer" />.
            </para>
          <para>
            Serialisierungsprogramme müssen unbegrenzt Rückwärtsrichtung kompatibel sein. Für die Typen, die integrierte Serialisierungsprogramme verwenden, stellt Service Fabric Aufwärts- und Abwärtskompatibilität sicher. Allerdings muss ein benutzerdefiniertes Serialisierers mit einem integrierten Serialisierungsprogramm für einen Typ hinzugefügt wird, kompatibel mit der integrierten Serialisierungsformat für diesen Typ der benutzerdefinierten Serialisierung sein.
            </para>
          <para>
            Diese Methode sollte vom Konstruktor der Stateful Service aufgerufen werden. Dadurch wird sichergestellt, dass die zuverlässige Auflistungen erforderlichen Serialisierungsprogramme aufweisen, vor Beginn der Wiederherstellung des persistenten Zustands.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.Fabric.TransactionFaultedException">Der Vorgang wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang</exception>
      </Docs>
    </Member>
  </Members>
</Type>