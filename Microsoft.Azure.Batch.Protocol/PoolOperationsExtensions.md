<Type Name="PoolOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PoolOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PoolOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PoolOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PoolOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für PoolOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Add (operations, pool, poolAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="pool">
            Der Pool hinzugefügt werden.
            </param>
        <param name="poolAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Das angegebene Konto hinzugefügt ein Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Benennen von Pools zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen. Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.AddAsync (operations, pool, poolAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;AddAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="pool">
            Der Pool hinzugefügt werden.
            </param>
        <param name="poolAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Das angegebene Konto hinzugefügt ein Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Benennen von Pools zu vermeiden, darunter vertrauliche Daten wie Benutzernamen oder für den geheimen Projektnamen. Diese Informationen erscheinen im Telemetrie-Protokolle an Microsoft Support-Mitarbeiter zugegriffen werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Delete (operations, poolId, poolDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools gelöscht werden soll.
            </param>
        <param name="poolDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht einen Pool aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie anfordern, dass ein Pool gelöscht werden, die folgenden Aktionen ausgeführt: der Zustand Pool ist festgelegt, zu löschen; Alle größenänderungsvorgang für den Pool beendet werden. der Batch-Dienst gestartet wird, Ändern der Größe des Pools Knoten NULL; Alle Aufgaben, die auf vorhandenen Knoten ausgeführt werden beendet und in die Warteschlange (wie bei der ein größenänderungsvorgang für den Pool mit der Standardoption wieder in Warteschlange angefordert worden); Schließlich wird der Pool aus dem System entfernt. Da Ausführen von Tasks in die Warteschlange sind, kann Benutzer diese Aufgaben erneut ausführen durch ihren Auftrag um einen anderen Pool als Ziel aktualisieren. Die Aufgaben können Sie in den neuen Pool ausführen. Wenn Sie das Verhalten wieder in Warteschlange überschreiben möchten, sollten Sie poolgrößenänderung explizit, um den Pool auf 0 (null) Größe zu verkleinern, bevor Sie den Pool löschen aufrufen. Wenn Sie für einen Pool im Status "gelöscht" aktualisieren, Patches oder Löschen von API-aufrufen, wird es mit dem HTTP-Statuscode 409 mit Fehlercode PoolBeingDeleted fehl.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DeleteAsync (operations, poolId, poolDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools gelöscht werden soll.
            </param>
        <param name="poolDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Pool aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie anfordern, dass ein Pool gelöscht werden, die folgenden Aktionen ausgeführt: der Zustand Pool ist festgelegt, zu löschen; Alle größenänderungsvorgang für den Pool beendet werden. der Batch-Dienst gestartet wird, Ändern der Größe des Pools Knoten NULL; Alle Aufgaben, die auf vorhandenen Knoten ausgeführt werden beendet und in die Warteschlange (wie bei der ein größenänderungsvorgang für den Pool mit der Standardoption wieder in Warteschlange angefordert worden); Schließlich wird der Pool aus dem System entfernt. Da Ausführen von Tasks in die Warteschlange sind, kann Benutzer diese Aufgaben erneut ausführen durch ihren Auftrag um einen anderen Pool als Ziel aktualisieren. Die Aufgaben können Sie in den neuen Pool ausführen. Wenn Sie das Verhalten wieder in Warteschlange überschreiben möchten, sollten Sie poolgrößenänderung explizit, um den Pool auf 0 (null) Größe zu verkleinern, bevor Sie den Pool löschen aufrufen. Wenn Sie für einen Pool im Status "gelöscht" aktualisieren, Patches oder Löschen von API-aufrufen, wird es mit dem HTTP-Statuscode 409 mit Fehlercode PoolBeingDeleted fehl.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders DisableAutoScale (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders DisableAutoScale(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScale(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions)" />
      <MemberSignature Language="F#" Value="static member DisableAutoScale : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScale (operations, poolId, poolDisableAutoScaleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Speicherpools auf dem die automatische Skalierung deaktiviert.
            </param>
        <param name="poolDisableAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Deaktiviert die automatische Skalierung für einen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt; DisableAutoScaleAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt; DisableAutoScaleAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScaleAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAutoScaleAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScaleAsync (operations, poolId, poolDisableAutoScaleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;DisableAutoScaleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Speicherpools auf dem die automatische Skalierung deaktiviert.
            </param>
        <param name="poolDisableAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert die automatische Skalierung für einen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders EnableAutoScale (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders EnableAutoScale(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScale(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions)" />
      <MemberSignature Language="F#" Value="static member EnableAutoScale : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScale (operations, poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools für die automatische Skalierung aktiviert.
            </param>
        <param name="poolEnableAutoScaleParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolEnableAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ermöglicht die automatische Skalierung für einen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird. Wenn automatische Skalierung des Pools derzeit deaktiviert ist, müssen Sie eine gültige automatische Skalierung Formel als Teil der Anforderung angeben. Wenn automatische Skalierung des Pools bereits aktiviert ist, können Sie eine neue Formel für automatische Skalierung und/oder eine neue Evaluierung Intervall angeben. Diese API kann nicht für den gleichen Pool verwendet werden mehr als einmal alle 30 Sekunden aufgerufen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt; EnableAutoScaleAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt; EnableAutoScaleAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScaleAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAutoScaleAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScaleAsync (operations, poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;EnableAutoScaleAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools für die automatische Skalierung aktiviert.
            </param>
        <param name="poolEnableAutoScaleParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolEnableAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermöglicht die automatische Skalierung für einen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können keine Aktivieren der automatischen Skalierung für einen Pool, wenn ein größenänderungsvorgang für den Pool ausgeführt wird. Wenn automatische Skalierung des Pools derzeit deaktiviert ist, müssen Sie eine gültige automatische Skalierung Formel als Teil der Anforderung angeben. Wenn automatische Skalierung des Pools bereits aktiviert ist, können Sie eine neue Formel für automatische Skalierung und/oder eine neue Evaluierung Intervall angeben. Diese API kann nicht für den gleichen Pool verwendet werden mehr als einmal alle 30 Sekunden aufgerufen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun EvaluateAutoScale (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun EvaluateAutoScale(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScale(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions)" />
      <MemberSignature Language="F#" Value="static member EvaluateAutoScale : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScale (operations, poolId, autoScaleFormula, poolEvaluateAutoScaleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Speicherpools auf dem die Formel für automatische Skalierung ausgewertet werden soll.
            </param>
        <param name="autoScaleFormula">
            Die Formel für die gewünschte Anzahl von Serverknoten im Pool. Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird. Um die Formel für den Pool anzuwenden, "Aktivieren der automatischen Skalierung für einen Pool". Weitere Informationen zum Angeben dieser Formel finden Sie unter automatisch skalieren Serverknoten in einem Azure Batch-Pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für den Pool Skalierung.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API ist in erster Linie für eine Formel für automatische Skalierung überprüfen, wie sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool. Der Pool muss die automatische Skalierung aktiviert, um eine Formel auswerten aufweisen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt; EvaluateAutoScaleAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt; EvaluateAutoScaleAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScaleAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EvaluateAutoScaleAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScaleAsync (operations, poolId, autoScaleFormula, poolEvaluateAutoScaleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;EvaluateAutoScaleAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Speicherpools auf dem die Formel für automatische Skalierung ausgewertet werden soll.
            </param>
        <param name="autoScaleFormula">
            Die Formel für die gewünschte Anzahl von Serverknoten im Pool. Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird. Um die Formel für den Pool anzuwenden, "Aktivieren der automatischen Skalierung für einen Pool". Weitere Informationen zum Angeben dieser Formel finden Sie unter automatisch skalieren Serverknoten in einem Azure Batch-Pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das Ergebnis der Auswertung einer Automatisches Formel für den Pool Skalierung.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese API ist in erster Linie für eine Formel für automatische Skalierung überprüfen, wie sie einfach das Ergebnis zurückgibt, ohne die Formel für den Pool. Der Pool muss die automatische Skalierung aktiviert, um eine Formel auswerten aufweisen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Exists(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions -&gt; bool" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Exists (operations, poolId, poolExistsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID der dem Pool abgerufen werden soll.
            </param>
        <param name="poolExistsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die grundlegende Eigenschaften eines Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ExistsAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ExistsAsync (operations, poolId, poolExistsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ExistsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID der dem Pool abgerufen werden soll.
            </param>
        <param name="poolExistsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die grundlegende Eigenschaften eines Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudPool Get (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudPool Get(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudPool" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Get (operations, poolId, poolGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID der dem Pool abgerufen werden soll.
            </param>
        <param name="poolGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft Informationen über den angegebenen Pool ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolStatistics GetAllLifetimeStatistics (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics GetAllLifetimeStatistics(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatistics(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatistics : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatistics (operations, poolGetAllLifetimeStatisticsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolGetAllLifetimeStatisticsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die Lebensdauer zusammenfassungsstatistiken für alle Pools im angegebenen Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt; GetAllLifetimeStatisticsAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt; GetAllLifetimeStatisticsAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatisticsAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatisticsAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatisticsAsync (operations, poolGetAllLifetimeStatisticsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;GetAllLifetimeStatisticsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolGetAllLifetimeStatisticsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Lebensdauer zusammenfassungsstatistiken für alle Pools im angegebenen Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Statistiken werden für alle Pools aggregiert, die jemals im Konto, von der kontoerstellung bis zum letzten Zeitpunkt des Updates der Statistik vorhanden waren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAsync (operations, poolId, poolGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID der dem Pool abgerufen werden soll.
            </param>
        <param name="poolGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Pool ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; List (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; List(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.List (operations, poolListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet alle Pools im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListAsync (operations, poolListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Pools im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNext (operations, nextPageLink, poolListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="poolListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet alle Pools im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNextAsync (operations, nextPageLink, poolListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="poolListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Pools im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetrics (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetrics(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetrics(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetrics : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetrics (operations, poolListUsageMetricsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolListUsageMetricsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Nutzungsdaten von Pool über einzelne Zeitintervalle, für das angegebene Konto aggregiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine $filter-Klausel, z. B. eine PoolId nicht angeben, enthält die Antwort alle Pools, die vorhanden waren in das Konto im Zeitraum von Intervallen zurückgegebenen Aggregation an. Wenn Sie keiner $filter-Klausel, einschließlich einer StartTime und EndTime diese Filter standardmäßig die Start- und Endzeiten des letzten aggregationsintervalls derzeit verfügbaren angeben; Das heißt, ist nur im letzte aggregationsintervall zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetricsAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsAsync (operations, poolListUsageMetricsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListUsageMetricsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolListUsageMetricsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Nutzungsdaten von Pool über einzelne Zeitintervalle, für das angegebene Konto aggregiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine $filter-Klausel, z. B. eine PoolId nicht angeben, enthält die Antwort alle Pools, die vorhanden waren in das Konto im Zeitraum von Intervallen zurückgegebenen Aggregation an. Wenn Sie keiner $filter-Klausel, einschließlich einer StartTime und EndTime diese Filter standardmäßig die Start- und Endzeiten des letzten aggregationsintervalls derzeit verfügbaren angeben; Das heißt, ist nur im letzte aggregationsintervall zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetricsNext (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetricsNext(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNext(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetricsNext : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNext (operations, nextPageLink, poolListUsageMetricsNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="poolListUsageMetricsNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Nutzungsdaten von Pool über einzelne Zeitintervalle, für das angegebene Konto aggregiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine $filter-Klausel, z. B. eine PoolId nicht angeben, enthält die Antwort alle Pools, die vorhanden waren in das Konto im Zeitraum von Intervallen zurückgegebenen Aggregation an. Wenn Sie keiner $filter-Klausel, einschließlich einer StartTime und EndTime diese Filter standardmäßig die Start- und Endzeiten des letzten aggregationsintervalls derzeit verfügbaren angeben; Das heißt, ist nur im letzte aggregationsintervall zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsNextAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsNextAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNextAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetricsNextAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNextAsync (operations, nextPageLink, poolListUsageMetricsNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListUsageMetricsNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="poolListUsageMetricsNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Nutzungsdaten von Pool über einzelne Zeitintervalle, für das angegebene Konto aggregiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie eine $filter-Klausel, z. B. eine PoolId nicht angeben, enthält die Antwort alle Pools, die vorhanden waren in das Konto im Zeitraum von Intervallen zurückgegebenen Aggregation an. Wenn Sie keiner $filter-Klausel, einschließlich einer StartTime und EndTime diese Filter standardmäßig die Start- und Endzeiten des letzten aggregationsintervalls derzeit verfügbaren angeben; Das heißt, ist nur im letzte aggregationsintervall zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Patch (operations, poolId, poolPatchParameter, poolPatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="poolPatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolPatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt nur die Pooleigenschaften, die in der Anforderung angegeben. Z. B. behält, wenn der Pool eine Startaufgabe zugeordnet wurde, und eine Anforderung keine Start-Task-Element, klicken Sie dann der Pool die vorhandene Startaufgabe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.PatchAsync (operations, poolId, poolPatchParameter, poolPatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;PatchAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="poolPatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolPatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt nur die Pooleigenschaften, die in der Anforderung angegeben. Z. B. behält, wenn der Pool eine Startaufgabe zugeordnet wurde, und eine Anforderung keine Start-Task-Element, klicken Sie dann der Pool die vorhandene Startaufgabe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders RemoveNodes (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders RemoveNodes(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodes(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions)" />
      <MemberSignature Language="F#" Value="static member RemoveNodes : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodes (operations, poolId, nodeRemoveParameter, poolRemoveNodesOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, von dem Sie die Knoten entfernen möchten.
            </param>
        <param name="nodeRemoveParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolRemoveNodesOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Entfernt einen Serverknoten aus dem angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dieser Vorgang kann nur ausgeführt, wenn es sich bei der Zuordnungsstatus des Pools gleichmäßig ist. Wenn dieser Vorgang ausgeführt wird, wechselt der Zuordnung von stabilen zum Ändern der Größe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt; RemoveNodesAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt; RemoveNodesAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodesAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveNodesAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodesAsync (operations, poolId, nodeRemoveParameter, poolRemoveNodesOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;RemoveNodesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, von dem Sie die Knoten entfernen möchten.
            </param>
        <param name="nodeRemoveParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolRemoveNodesOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entfernt einen Serverknoten aus dem angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dieser Vorgang kann nur ausgeführt, wenn es sich bei der Zuordnungsstatus des Pools gleichmäßig ist. Wenn dieser Vorgang ausgeführt wird, wechselt der Zuordnung von stabilen zum Ändern der Größe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders Resize (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders Resize(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Resize(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions)" />
      <MemberSignature Language="F#" Value="static member Resize : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Resize (operations, poolId, poolResizeParameter, poolResizeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, um die Größe.
            </param>
        <param name="poolResizeParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolResizeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ändert die Anzahl von Compute-Knoten, die zu einem Pool zugewiesen sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Pool nur ändern, wenn seine Zuordnungsstatus gleichmäßig ist. Wenn der Pool bereits Größe ist, schlägt die Anforderung mit Statuscode 409 fehl. Wenn die Größe ändern Sie eines Pools, den Pool Zuordnung statusänderungen von stabilen zum Ändern der Größe.
            Pools, die für die automatische Skalierung konfiguriert sind, kann nicht geändert werden. Wenn Sie dies versuchen, gibt der Batch-Dienst einen Fehler 409 zurück. Wenn Sie einen Pool abwärts verkleinern, wählt der Batch-Dienst die Knoten aus, zu entfernen. Um bestimmte Knoten zu entfernen, verwenden Sie stattdessen den Pool Entfernen von Knoten API.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt; ResizeAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt; ResizeAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ResizeAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResizeAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ResizeAsync (operations, poolId, poolResizeParameter, poolResizeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ResizeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, um die Größe.
            </param>
        <param name="poolResizeParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolResizeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ändert die Anzahl von Compute-Knoten, die zu einem Pool zugewiesen sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Pool nur ändern, wenn seine Zuordnungsstatus gleichmäßig ist. Wenn der Pool bereits Größe ist, schlägt die Anforderung mit Statuscode 409 fehl. Wenn die Größe ändern Sie eines Pools, den Pool Zuordnung statusänderungen von stabilen zum Ändern der Größe.
            Pools, die für die automatische Skalierung konfiguriert sind, kann nicht geändert werden. Wenn Sie dies versuchen, gibt der Batch-Dienst einen Fehler 409 zurück. Wenn Sie einen Pool abwärts verkleinern, wählt der Batch-Dienst die Knoten aus, zu entfernen. Um bestimmte Knoten zu entfernen, verwenden Sie stattdessen den Pool Entfernen von Knoten API.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders StopResize (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders StopResize(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResize(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions)" />
      <MemberSignature Language="F#" Value="static member StopResize : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResize (operations, poolId, poolStopResizeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, dessen Größenänderung Sie beenden möchten.
            </param>
        <param name="poolStopResizeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Beendet einen aktiven größenänderungsvorgang für den Pool an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies wird den Pool nicht auf den ursprünglichen Zustand vor der Größenänderung wiederhergestellt: nur beendet wird, keine weiteren Änderungen vorgenommen werden, und der Pool behält den aktuellen Zustand. Nach dem Beenden stabilisiert der Pool an die Anzahl der Knoten, den sie an, wenn der Beendigungsvorgang abgeschlossen wurde. Während des Beendigungsvorgangs ändert den Zuordnungsstatus des Pools zunächst zu beenden und dann zu gleichmäßig. Ein größenänderungsvorgang muss eine explizite Resize Pool-Anfrage nicht. Diese API kann auch verwendet werden, auf die anfängliche Größe des Pools anhalten, wenn es erstellt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt; StopResizeAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt; StopResizeAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResizeAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopResizeAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResizeAsync (operations, poolId, poolStopResizeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;StopResizeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, dessen Größenänderung Sie beenden möchten.
            </param>
        <param name="poolStopResizeOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet einen aktiven größenänderungsvorgang für den Pool an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies wird den Pool nicht auf den ursprünglichen Zustand vor der Größenänderung wiederhergestellt: nur beendet wird, keine weiteren Änderungen vorgenommen werden, und der Pool behält den aktuellen Zustand. Nach dem Beenden stabilisiert der Pool an die Anzahl der Knoten, den sie an, wenn der Beendigungsvorgang abgeschlossen wurde. Während des Beendigungsvorgangs ändert den Zuordnungsstatus des Pools zunächst zu beenden und dann zu gleichmäßig. Ein größenänderungsvorgang muss eine explizite Resize Pool-Anfrage nicht. Diese API kann auch verwendet werden, auf die anfängliche Größe des Pools anhalten, wenn es erstellt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders UpdateProperties (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders UpdateProperties(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdateProperties(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions)" />
      <MemberSignature Language="F#" Value="static member UpdateProperties : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdateProperties (operations, poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="poolUpdatePropertiesParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolUpdatePropertiesOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Vollständig ersetzt alle aktualisierbaren Eigenschaften des Pools. Z. B. wenn der Pool eine Startaufgabe zugeordnet und Startaufgabe nicht mit dieser Anforderung angegeben ist, entfernen Sie dann der Batch-Dienst wird die vorhandene Startaufgabe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt; UpdatePropertiesAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt; UpdatePropertiesAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdatePropertiesAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePropertiesAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdatePropertiesAsync (operations, poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;UpdatePropertiesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="poolUpdatePropertiesParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="poolUpdatePropertiesOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Vollständig ersetzt alle aktualisierbaren Eigenschaften des Pools. Z. B. wenn der Pool eine Startaufgabe zugeordnet und Startaufgabe nicht mit dieser Anforderung angegeben ist, entfernen Sie dann der Batch-Dienst wird die vorhandene Startaufgabe.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeOS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders UpgradeOS (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders UpgradeOS(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOS(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions)" />
      <MemberSignature Language="F#" Value="static member UpgradeOS : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOS (operations, poolId, targetOSVersion, poolUpgradeOSOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="targetOSVersion">
            Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.
            </param>
        <param name="poolUpgradeOSOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert das Betriebssystem des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Während eines Upgrades Berechnen der Batch-dienstupgrades jeder Knoten im Pool. Wenn Compute-Knoten für das Upgrade ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und zurück an die Warteschlange erneut höher (oder auf einem anderen Serverknoten) ausgeführt wird. Der Knoten wird nicht verfügbar sein, bis das Upgrade abgeschlossen ist. Dieser Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb genommen werden, aktualisiert werden. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, aktualisieren alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); aus diesem Grund möglicherweise der Pool vorübergehend nicht verfügbar, um Aufgaben auszuführen. Wenn dieser Vorgang ausgeführt wird, wechselt der Pool zu aktualisieren. Wenn alle compute-Knoten die Aktualisierung beendet haben, wird der Poolstatus auf aktiv zurückgegeben. Während des Upgrades ausgeführt wird, gibt dem Pool CurrentOSVersion TargetOSVersion widerspiegelt, die Betriebssystemversion, der Knoten zu aktualisieren, dass Knoten ein Upgrade von der Betriebssystemversion an. Nachdem das Upgrade abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird. Dieser Vorgang kann nur auf mit der Eigenschaft CloudServiceConfiguration erstellten Ressourcenpools aufgerufen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeOSAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt; UpgradeOSAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt; UpgradeOSAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOSAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeOSAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOSAsync (operations, poolId, targetOSVersion, poolUpgradeOSOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;UpgradeOSAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools aktualisieren.
            </param>
        <param name="targetOSVersion">
            Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.
            </param>
        <param name="poolUpgradeOSOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das Betriebssystem des angegebenen Pools.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Während eines Upgrades Berechnen der Batch-dienstupgrades jeder Knoten im Pool. Wenn Compute-Knoten für das Upgrade ausgewählt ist, sind alle Aufgaben, die auf diesem Knoten ausgeführt wird aus dem Knoten entfernt und zurück an die Warteschlange erneut höher (oder auf einem anderen Serverknoten) ausgeführt wird. Der Knoten wird nicht verfügbar sein, bis das Upgrade abgeschlossen ist. Dieser Vorgang führt zu vorübergehend reduzierte Pool-Kapazität, wie Knoten außer Betrieb genommen werden, aktualisiert werden. Obwohl die Batch-Dienst versucht wird, um zu vermeiden, aktualisieren alle Serverknoten zur gleichen Zeit, garantiert jedoch nicht dazu (vor allem für kleine Pools); aus diesem Grund möglicherweise der Pool vorübergehend nicht verfügbar, um Aufgaben auszuführen. Wenn dieser Vorgang ausgeführt wird, wechselt der Pool zu aktualisieren. Wenn alle compute-Knoten die Aktualisierung beendet haben, wird der Poolstatus auf aktiv zurückgegeben. Während des Upgrades ausgeführt wird, gibt dem Pool CurrentOSVersion TargetOSVersion widerspiegelt, die Betriebssystemversion, der Knoten zu aktualisieren, dass Knoten ein Upgrade von der Betriebssystemversion an. Nachdem das Upgrade abgeschlossen ist, wird CurrentOSVersion aktualisiert, entsprechend der Version des Betriebssystems nun auf allen Knoten ausgeführt wird. Dieser Vorgang kann nur auf mit der Eigenschaft CloudServiceConfiguration erstellten Ressourcenpools aufgerufen werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>