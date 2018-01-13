<Type Name="IDomainManager&lt;TData&gt;" FullName="Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt;">
  <TypeSignature Language="C#" Value="public interface IDomainManager&lt;TData&gt; where TData : class, ITableData" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDomainManager`1&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDomainManager(Of TData)" />
  <TypeSignature Language="F#" Value="type IDomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TData">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TData"></typeparam>
    <summary>
            Stellt eine Abstraktion für den Zugriff auf einen Back-End-Speicher für eine <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.
            Die Abstraktion kann auf zwei Arten abhängig von den Funktionen des Back-End-Speichers implementiert werden. Speichert, unterstützen einen <see cref="T:System.Linq.IQueryable`1" />-basierendes Modell kann Implementieren der <see cref="M:Query" /> und <see cref="M:Lookup" /> Methoden während speichert, die nicht unterstützen <see cref="T:System.Linq.IQueryable" /> direkt und wo es ist nicht die bevorzugte Methode für den Zugriff auf die sie implementieren kann die <see cref="M:QueryAsync" /> und <see cref="M:LookupAsync" /> Methoden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.DeleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (id As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iDomainManager.DeleteAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die Id des Elements, das gelöscht werden soll.</param>
        <summary>
            Löscht ein vorhandenes Element
            </summary>
        <returns>
          <c>"true"</c> Wenn Element gelöscht; andernfalls wurde <c>"false"</c></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; InsertAsync (TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; InsertAsync(!TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.InsertAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="data">Die Daten eingefügt werden</param>
        <summary>
            Fügt ein Element in den Back-End-Speicher.
            </summary>
        <returns>Das eingefügte Element.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lookup">
      <MemberSignature Language="C#" Value="public System.Web.Http.SingleResult&lt;TData&gt; Lookup (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; Lookup(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Lookup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Lookup (id As String) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Lookup : string -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.Lookup id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die Id, die das Element darstellt. Die Id dient als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> und an den Client sichtbar ist. Jedoch kann die jeweiligen Implementierung abhängig von den Back-End-Speicher und das Domänenmodell, die Id in eine andere Form der eindeutige Bezeichner zuordnen.</param>
        <summary>
            Erstellt ein <see cref="T:System.Linq.IQueryable`1" /> gegen ein Store unterstützender auszuführenden <see cref="T:System.Linq.IQueryable`1" /> für ein einzelnes Element nachschlagen.
            </summary>
        <returns>Ein <see cref="T:System.Web.Http.SingleResult`1" /> , enthält die <see cref="T:System.Linq.IQueryable`1" /> der wurde noch nicht ausgeführt wurde.</returns>
        <remarks>
            Siehe auch <see cref="M:Query" /> also die Begleitmethode zum Erstellen einer <see cref="T:System.Linq.IQueryable`1" /> , die mehrere Elemente darstellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.SingleResult`1&lt;!TData&gt;&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of SingleResult(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;" Usage="iDomainManager.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die Id, die das Element darstellt. Die Id dient als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> und an den Client sichtbar ist. Jedoch kann die jeweiligen Implementierung abhängig von den Back-End-Speicher und das Domänenmodell, die Id in eine andere Form der eindeutige Bezeichner zuordnen.</param>
        <summary>
            Sucht ein einzelnes Element im Back-End-Speicher. 
            </summary>
        <returns>Ein <see cref="T:System.Web.Http.SingleResult`1" /> , das dem Ergebnis der Suche. Ein <see cref="T:System.Web.Http.SingleResult`1" /> stellt eine <see cref="T:System.Linq.IQueryable" /> mit keinem oder einem Entitäten. Dadurch kann er mit einer weiteren Abfrage z. B. gebildet werden <c>$select</c>.</returns>
        <remarks>
            Siehe auch <see cref="M:QueryAsync" /> die Begleitmethode zum Ausführen einer Abfrage für mehrere Elemente ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;TData&gt; Query ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!TData&gt; Query() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Query" />
      <MemberSignature Language="VB.NET" Value="Public Function Query () As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.Query " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt ein <see cref="T:System.Linq.IQueryable`1" /> gegen ein Store unterstützender auszuführenden <see cref="T:System.Linq.IQueryable`1" /> zum Abfragen von Daten. 
            </summary>
        <returns>Ein <see cref="T:System.Linq.IQueryable`1" /> der wurde noch nicht ausgeführt wurde.</returns>
        <remarks>
            Siehe auch <see cref="M:Lookup" /> also die Begleitmethode zum Erstellen einer <see cref="T:System.Linq.IQueryable`1" /> , die ein einzelnes Element darstellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt; QueryAsync (System.Web.Http.OData.Query.ODataQueryOptions query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!TData&gt;&gt; QueryAsync(class System.Web.Http.OData.Query.ODataQueryOptions query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueryAsync (query As ODataQueryOptions) As Task(Of IEnumerable(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;" Usage="iDomainManager.QueryAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
      </Parameters>
      <Docs>
        <param name="query">Die <see cref="T:System.Web.Http.OData.Query.ODataQueryOptions" /> auszuführende Abfrage.</param>
        <summary>
            Führt die bereitgestellte <paramref name="query" /> für einen Speicher.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> , das dem Ergebnis der Abfrage.</returns>
        <remarks>
            Siehe auch <see cref="M:LookupAsync" /> also die Begleitmethode für das Ausführen einer Suche für ein einzelnes Element.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; ReplaceAsync (string id, TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; ReplaceAsync(string id, !TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.ReplaceAsync(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceAsync (id As String, data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.ReplaceAsync (id, data)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="id">Die Id des zu ersetzenden Elements.</param>
        <param name="data">Die Ersetzung</param>
        <summary>
            Vollständig ersetzt ein vorhandenes Element aus.
            </summary>
        <returns>Das ersetzte Element</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TData&gt; UpdateAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="iDomainManager.UpdateAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Die Id des Elements, das Patch.</param>
        <param name="patch">Der Patch angewendet werden soll.</param>
        <summary>
            Aktualisiert ein vorhandenes Element durch Anwenden einer <see cref="T:System.Web.Http.OData.Delta`1" /> Patch darauf. Die <see cref="T:System.Web.Http.OData.Delta`1" /> Abstraktion der nachverfolgt welche Eigenschaften geändert haben, die Probleme mit Standardwerten und wie vermeidet.
            </summary>
        <returns>Das Patch-Element.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>