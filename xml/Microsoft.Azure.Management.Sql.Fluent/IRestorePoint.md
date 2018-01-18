<Type Name="IRestorePoint" FullName="Microsoft.Azure.Management.Sql.Fluent.IRestorePoint">
  <TypeSignature Language="C#" Value="public interface IRestorePoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRestorePoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IRestorePoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRestorePoint&#xA;Implements IHasId, IHasInner(Of RestorePointInner), IHasName, IHasResourceGroup" />
  <TypeSignature Language="F#" Value="type IRestorePoint = interface&#xA;    interface IHasInner&lt;RestorePointInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1e326-101">Eine unveränderliche clientseitige Darstellung des Wiederherstellungspunkts für einer Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="1e326-101">An immutable client-side representation of an Azure SQL database's Restore Point.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e326-102">Ruft die Namen der SQL-Datenbank, zu der diese Replikation gehört.</span><span class="sxs-lookup"><span data-stu-id="1e326-102">Gets name of the SQL Database to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public DateTime EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As DateTime" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e326-103">Ruft Wiederherstellungszeit frühesten (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1e326-103">Gets earliest restore time (ISO8601 format).</span></span> <span data-ttu-id="1e326-104">Aufgefüllt, wenn RestorePointType = diskrete Werte.</span><span class="sxs-lookup"><span data-stu-id="1e326-104">Populated when restorePointType = DISCRETE.</span></span> <span data-ttu-id="1e326-105">Andernfalls NULL.</span><span class="sxs-lookup"><span data-stu-id="1e326-105">Null otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointCreationDate">
      <MemberSignature Language="C#" Value="public DateTime RestorePointCreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime RestorePointCreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.RestorePointCreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorePointCreationDate As DateTime" />
      <MemberSignature Language="F#" Value="member this.RestorePointCreationDate : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.RestorePointCreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e326-106">Ruft Restore Point-Erstellungszeit (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1e326-106">Gets restore point creation time (ISO8601 format).</span></span> <span data-ttu-id="1e326-107">Aufgefüllt, wenn RestorePointType = FORTLAUFEND.</span><span class="sxs-lookup"><span data-stu-id="1e326-107">Populated when restorePointType = CONTINUOUS.</span></span> <span data-ttu-id="1e326-108">Andernfalls NULL.</span><span class="sxs-lookup"><span data-stu-id="1e326-108">Null otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes RestorePointType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes RestorePointType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.RestorePointType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorePointType As RestorePointTypes" />
      <MemberSignature Language="F#" Value="member this.RestorePointType : Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes" Usage="Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.RestorePointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e326-109">Ruft den Typ des Restore-Punkts des Wiederherstellungspunkts Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="1e326-109">Gets the restore point type of the Azure SQL Database restore point.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IRestorePoint.SqlServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e326-110">Ruft die Namen von SQL Server, der diese Replikation angehört.</span><span class="sxs-lookup"><span data-stu-id="1e326-110">Gets name of the SQL Server to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>