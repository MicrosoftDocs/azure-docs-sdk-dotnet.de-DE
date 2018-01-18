<Type Name="ITransparentDataEncryption" FullName="Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption">
  <TypeSignature Language="C#" Value="public interface ITransparentDataEncryption : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransparentDataEncryption implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransparentDataEncryption&#xA;Implements IHasId, IHasInner(Of TransparentDataEncryptionInner), IHasName, IHasResourceGroup" />
  <TypeSignature Language="F#" Value="type ITransparentDataEncryption = interface&#xA;    interface IHasInner&lt;TransparentDataEncryptionInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</InterfaceName>
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
            <span data-ttu-id="16977-101">Eine unveränderliche clientseitige Darstellung von TransparentDataEncryption für eine Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="16977-101">An immutable client-side representation of an Azure SQL database's TransparentDataEncryption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.DatabaseName" />
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
            <span data-ttu-id="16977-102">Ruft die Namen der SQL-Datenbank, zu der diese Replikation gehört.</span><span class="sxs-lookup"><span data-stu-id="16977-102">Gets name of the SQL Database to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListActivities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryptionActivity&gt; ListActivities ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryptionActivity&gt; ListActivities() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.ListActivities" />
      <MemberSignature Language="VB.NET" Value="Public Function ListActivities () As IReadOnlyList(Of ITransparentDataEncryptionActivity)" />
      <MemberSignature Language="F#" Value="abstract member ListActivities : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryptionActivity&gt;" Usage="iTransparentDataEncryption.ListActivities " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryptionActivity&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="16977-103">Eine Azure SQL-Datenbank Transparent Data Encryption-Aktivitäten.</span><span class="sxs-lookup"><span data-stu-id="16977-103">An Azure SQL Database Transparent Data Encryption Activities.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.SqlServerName" />
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
            <span data-ttu-id="16977-104">Ruft die Namen von SQL Server, der diese Replikation angehört.</span><span class="sxs-lookup"><span data-stu-id="16977-104">Gets name of the SQL Server to which this replication belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As TransparentDataEncryptionStates" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates" Usage="Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16977-105">Ruft den Status der Azure SQL-Datenbank Transparent Data Encryption.</span><span class="sxs-lookup"><span data-stu-id="16977-105">Gets the status of the Azure SQL Database Transparent Data Encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption UpdateStatus (Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates transparentDataEncryptionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption UpdateStatus(valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates transparentDataEncryptionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption.UpdateStatus(Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateStatus (transparentDataEncryptionState As TransparentDataEncryptionStates) As ITransparentDataEncryption" />
      <MemberSignature Language="F#" Value="abstract member UpdateStatus : Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates -&gt; Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption" Usage="iTransparentDataEncryption.UpdateStatus transparentDataEncryptionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ITransparentDataEncryption</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transparentDataEncryptionState" Type="Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates" />
      </Parameters>
      <Docs>
        <param name="transparentDataEncryptionState"><span data-ttu-id="16977-106">Status der datenverschlüsselung festgelegt.</span><span class="sxs-lookup"><span data-stu-id="16977-106">State of the data encryption to set.</span></span></param>
        <summary>
            <span data-ttu-id="16977-107">Der Status des transparent Data Encryption Status aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="16977-107">Updates the state of the transparent data encryption status.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="16977-108">Die neuen Einstellungen für die Verschlüsselung nach modifiyState.</span><span class="sxs-lookup"><span data-stu-id="16977-108">The new encryption settings after modifyState.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>