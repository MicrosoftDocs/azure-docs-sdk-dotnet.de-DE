<Type Name="ISqlWarehouse" FullName="Microsoft.Azure.Management.Sql.Fluent.ISqlWarehouse">
  <TypeSignature Language="C#" Value="public interface ISqlWarehouse : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate&gt;, Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlWarehouse implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate&gt;, class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ISqlWarehouse" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlWarehouse&#xA;Implements IGroupableResource(Of ISqlManager, DatabaseInner), IHasInner(Of DatabaseInner), IHasManager(Of ISqlManager), IIndependentChild(Of ISqlManager), IIndependentChildResource(Of ISqlManager, DatabaseInner), IRefreshable(Of ISqlDatabase), ISqlDatabase, IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ISqlWarehouse = interface&#xA;    interface ISqlDatabase&#xA;    interface IIndependentChildResource&lt;ISqlManager, DatabaseInner&gt;&#xA;    interface IGroupableResource&lt;ISqlManager, DatabaseInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;ISqlManager&gt;&#xA;    interface IHasInner&lt;DatabaseInner&gt;&#xA;    interface IIndependentChild&lt;ISqlManager&gt;&#xA;    interface IRefreshable&lt;ISqlDatabase&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Update.IUpdate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung einer Azure SQL Datawarehouse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PauseDataWarehouse">
      <MemberSignature Language="C#" Value="public void PauseDataWarehouse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PauseDataWarehouse() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlWarehouse.PauseDataWarehouse" />
      <MemberSignature Language="VB.NET" Value="Public Sub PauseDataWarehouse ()" />
      <MemberSignature Language="F#" Value="abstract member PauseDataWarehouse : unit -&gt; unit" Usage="iSqlWarehouse.PauseDataWarehouse " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Anhalten einer Azure SQL Data Warehouse-Datenbank.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PauseDataWarehouseAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PauseDataWarehouseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlWarehouse.PauseDataWarehouseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PauseDataWarehouseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSqlWarehouse.PauseDataWarehouseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Halten Sie eine Azure SQL Data Warehouse-Datenbank asynchron.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="ResumeDataWarehouse">
      <MemberSignature Language="C#" Value="public void ResumeDataWarehouse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResumeDataWarehouse() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlWarehouse.ResumeDataWarehouse" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResumeDataWarehouse ()" />
      <MemberSignature Language="F#" Value="abstract member ResumeDataWarehouse : unit -&gt; unit" Usage="iSqlWarehouse.ResumeDataWarehouse " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Fortsetzen einer Azure SQL Data Warehouse-Datenbank.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResumeDataWarehouseAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResumeDataWarehouseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlWarehouse.ResumeDataWarehouseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeDataWarehouseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSqlWarehouse.ResumeDataWarehouseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Eine Azure SQL Data Warehouse-Datenbank asynchron fortgesetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
  </Members>
</Type>