<Type Name="ODATADetailLevel" FullName="Microsoft.Azure.Batch.ODATADetailLevel">
  <TypeSignature Language="C#" Value="public class ODATADetailLevel : Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ODATADetailLevel extends Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ODATADetailLevel" />
  <TypeSignature Language="VB.NET" Value="Public Class ODATADetailLevel&#xA;Inherits DetailLevel" />
  <TypeSignature Language="F#" Value="type ODATADetailLevel = class&#xA;    inherit DetailLevel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.DetailLevel</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             Steuert die Anzahl der Details aus dem Azure Batch-Dienst beim Auflisten oder Abrufen von Ressourcen, die mithilfe von OData-Abfrageklauseln angefordert.
             </summary>
    <remarks>
      <para>Azure Batch unterstützt OData-Abfragen, die dem Client erlauben, erhalten eine präzisere Steuerung der Leistung von Abfragen, indem Sie steuern, welche Ressourcen in Auflistungsvorgänge zurückgegeben werden (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />), und welche Eigenschaften jeder Ressource zurückgegeben werden, in der Liste "," Get "oder" Aktualisieren Vorgänge (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" /> und <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />).</para>
      <para>Standardmäßig, wenn Sie nicht bestehen, eine <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> auf eine Liste abrufen oder Aktualisieren der Batch-Client gibt kein Filter (alle Datensätze zurückgegeben werden), keine select-Klausel (alle einfache Eigenschaften werden zurückgegeben) und keine expand-Klausel (zugehörigen Entitäten werden nicht zurückgegeben).  Daher sind Eigenschaften der zugeordneten Entität standardmäßig Null, anstatt wie andere Eigenschaften aufgefüllt wird.  Finden Sie in der Dokumentation der einzelnen um herauszufinden, welche Eigenschaften gelten als zugehörigen Entitäten und erweitert werden, um die aufgefüllt werden müssen.</para>
      <para>Da die OData-Abfragen direkt an die REST-API übergeben werden, müssen Klausel Zeichenfolgen die JSON-Attributnamen aus der REST-API verwenden, die nicht immer den Eigenschaftennamen .NET entsprechen.  Beispielsweise .NET <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize">CloudPool.VirtualMachineSize</see> Eigenschaft entspricht dem VmSize-Attribut in der REST-API; deshalb einen Pool Auflisten von Vorgängen nach Größe des virtuellen Computers filtern möchten, müssen Sie VmSize statt VirtualMachineSize schreiben in der Filterzeichenfolge.  Finden Sie in der REST-API-Dokumentation so ermitteln Sie den Namen des JSON-Attributs entspricht einer Eigenschaft .NET.</para>
      <para>Weitere Informationen zur Verwendung von OData zum effizienten Abfragen der Azure Batch-Dienst finden Sie unter <a href="https://azure.microsoft.com/en-us/documentation/articles/batch-efficient-list-queries/">effiziente Listenabfragen</a> auf MSDN.</para>
    </remarks>
    <example>
             In diesem Beispiel wird gezeigt, wie ein ODataDetailLevel angeben, die nur aktiv listet <see cref="T:Microsoft.Azure.Batch.CloudPool">CloudPools</see>, und ruft nur die <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />, <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> für jeden Pool (z. B. für die Anzeige in einem reporting-Benutzer -Schnittstelle).
             <code>
             var detailLevel = new ODATADetailLevel(
             filterClause: "state eq 'active'",
             selectClause: "id,displayName,stats",
                 expandClause: "stats"
                 );
                 
             var pools = batchClient.PoolOperations.ListPools(detailLevel);
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> Klasse mit leeren-Klauseln.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel (string filterClause = null, string selectClause = null, string expandClause = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filterClause, string selectClause, string expandClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filterClause As String = null, Optional selectClause As String = null, Optional expandClause As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ODATADetailLevel : string * string * string -&gt; Microsoft.Azure.Batch.ODATADetailLevel" Usage="new Microsoft.Azure.Batch.ODATADetailLevel (filterClause, selectClause, expandClause)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filterClause" Type="System.String" />
        <Parameter Name="selectClause" Type="System.String" />
        <Parameter Name="expandClause" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterClause">Die Filterklausel.</param>
        <param name="selectClause">Die SELECT-Klausel.</param>
        <param name="expandClause">Der Expand-Klausel.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> Klasse mit der angegebenen Klausel.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandClause">
      <MemberSignature Language="C#" Value="public string ExpandClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpandClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandClause As String" />
      <MemberSignature Language="F#" Value="member this.ExpandClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die OData expand-Klausel. Verwendet zum Abrufen der zugehörigen Entitäten der Hauptentität abgerufen wird.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Dies ist ein optionaler OData $expand-Ausdruckszeichenfolge <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398162">(siehe die OData-Spezifikation)</a>.
            Eigenschaften, die zugehörigen Entitäten enthält werden null, wenn in einer ExpandClause eingeschlossen.
            Insbesondere wenn Sie eine Liste durchführen, abzurufen Sie oder zu aktualisieren Sie und geben Sie eine ExpandClause nicht an, und klicken Sie dann alle Eigenschaften der zugeordneten Entität auf null werden.  Angenommen, Sie führen eine <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Vorgang ohne eine ExpandClause die <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> -Eigenschaft wird null sein.  Zum Auffüllen der Eigenschaft Statistics müssen Sie angeben, ein ExpandClause von <c>Stats</c>.  Finden Sie in einzelne Klassendokumentation, um herauszufinden, welche Eigenschaften zugeordneten Entitäten berücksichtigt werden.</para>
          <para>Wenn Sie sowohl eine ExpandClause angeben und eine <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />, und klicken Sie dann in der ExpandClause aufgeführten Eigenschaften in der SelectClause wiederholt werden müssen (da nur die in der SelectClause aufgeführten Eigenschaften in der Antwort des Diensts enthalten sind).  (Diese Anforderung nicht auftreten können, wenn Sie eine SelectClause nicht angeben, bedeutet dies, dass "umfassen alle Eigenschaften in der Antwort.")</para>
          <para>Erweiterungen müssen mithilfe von REST-API-Attributnamen, nicht .NET Eigenschaftennamen angegeben werden.</para>
          <para>Die Standardeinstellung ist keine erweitern Ausdruck, d. h. keine zugewiesenen Objekte zurückgegeben werden (und die entsprechenden Eigenschaften sind null).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterClause">
      <MemberSignature Language="C#" Value="public string FilterClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterClause As String" />
      <MemberSignature Language="F#" Value="member this.FilterClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die OData-Filter-Klausel. Verwendet, um ein listenvorgang, um Elemente zu beschränken, die angegebenen Kriterien entsprechen.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Dies ist eine optionale OData $filter Ausdruckszeichenfolge <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398094">(siehe die OData-Spezifikation)</a>.
            Sie können z. B. Einschränken einer <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Vorgang nur die aktiven Pools mit dem Ausdruck zurückgeben <c>State Eq 'aktiv'</c>.</para>
          <para>Verwenden von REST-API-Attributnamen, nicht .NET Eigenschaftennamen müssen Filter angegeben werden.</para>
          <para>Der Standardwert ist kein Filterausdruck, was bedeutet, dass alle Ressourcen zurückgegeben werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectClause">
      <MemberSignature Language="C#" Value="public string SelectClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelectClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectClause As String" />
      <MemberSignature Language="F#" Value="member this.SelectClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die OData-select-Klausel. Verwendet, um nur bestimmte Eigenschaften alle Eigenschaften des Objekts abzurufen.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Dies ist eine optionale OData $select Ausdruckszeichenfolge <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398163">(siehe die OData-Spezifikation)</a>.
            Wenn Sie eine SelectClause dann bereitstellen <b>nur</b> werden die Eigenschaften aufgeführt, die in dieser Klausel aufgefüllt; andere Eigenschaften verfügen über die Standardwerte (in der Regel null).  Angenommen, Sie führen eine <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> Vorgang mit einem SelectClause von <c>-Id, DisplayName</c>, klicken Sie dann jede <see cref="T:Microsoft.Azure.Batch.CloudPool" /> müssen die <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> und <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> Eigenschaften aufgefüllt, jedoch andere Eigenschaften wie z. B. <see cref="P:Microsoft.Azure.Batch.CloudPool.State" /> nicht abgerufen werden soll, und aus diesem Grund müssen die Standardwerte (in der Regel null).</para>
          <para>Wenn bei eine Entität (über eine Liste abrufen oder aktualisieren) abgerufen wurde, identifizieren angegebene eine SelectClause, die nicht die Eigenschaft bzw. Eigenschaften eindeutig, enthält das Objekt (normalerweise die Id-Eigenschaft, aber für <see cref="T:Microsoft.Azure.Batch.Certificate" /> den Fingerabdruck und ThumbprintAlgorithm Eigenschaften, und klicken Sie dann auf alle Methoden, die Zugriff auf die Batch-Dienst zum Abrufen von Daten oder Vorgänge ausführen, schlägt fehl.
            Dazu gehören die meisten Methoden für das Objekt, einschließlich <see cref="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> und <see cref="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.
            Sie können Eigenschaften weiterhin zugegriffen werden (obwohl nur in der SelectClause enthaltenen Eigenschaften aufgefüllt werden).</para>
          <para>Verwenden von REST-API-Attributnamen, die Eigenschaftennamen nicht .NET müssen die Auswahl angegeben werden.</para>
          <para>Der Standardwert ist keine select-Ausdruck, was bedeutet, dass alle Eigenschaften zurückgegeben werden.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>