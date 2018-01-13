<Type Name="AccessControlRecordsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AccessControlRecordsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AccessControlRecordsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AccessControlRecordsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AccessControlRecordsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für AccessControlRecordsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IAccessControlRecordsOperations, accessControlRecordName As String, parameters As AccessControlRecord, resourceGroupName As String, managerName As String) As AccessControlRecord" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdate (operations, accessControlRecordName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record.
            </param>
        <param name="parameters">
            Access Control Record hinzugefügt oder aktualisiert werden soll.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Erstellt oder aktualisiert einen Access-Control-Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdateAsync (operations, accessControlRecordName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record.
            </param>
        <param name="parameters">
            Access Control Record hinzugefügt oder aktualisiert werden soll.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Access-Control-Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IAccessControlRecordsOperations, accessControlRecordName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDelete (operations, accessControlRecordName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record zu löschen.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Löscht den zugriffssteuerungsdatensatz an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDeleteAsync (operations, accessControlRecordName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record zu löschen.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den zugriffssteuerungsdatensatz an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAccessControlRecordsOperations, accessControlRecordName As String, parameters As AccessControlRecord, resourceGroupName As String, managerName As String) As AccessControlRecord" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdate (operations, accessControlRecordName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record.
            </param>
        <param name="parameters">
            Access Control Record hinzugefügt oder aktualisiert werden soll.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Erstellt oder aktualisiert einen Access-Control-Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdateAsync (operations, accessControlRecordName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record.
            </param>
        <param name="parameters">
            Access Control Record hinzugefügt oder aktualisiert werden soll.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Access-Control-Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAccessControlRecordsOperations, accessControlRecordName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Delete (operations, accessControlRecordName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record zu löschen.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Löscht den zugriffssteuerungsdatensatz an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.DeleteAsync (operations, accessControlRecordName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Der Name des Access Control Record zu löschen.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den zugriffssteuerungsdatensatz an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord Get (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord Get(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAccessControlRecordsOperations, accessControlRecordName As String, resourceGroupName As String, managerName As String) As AccessControlRecord" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Get (operations, accessControlRecordName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Name des zugriffssteuerungsdatensatzes abgerufen werden sollen.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Die Eigenschaften des angegebenen Access Control-Datensatznamens zurückgegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.GetAsync (operations, accessControlRecordName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="accessControlRecordName">
            Name des zugriffssteuerungsdatensatzes abgerufen werden sollen.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die Eigenschaften des angegebenen Access Control-Datensatznamens zurückgegeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IAccessControlRecordsOperations, resourceGroupName As String, managerName As String) As IEnumerable(Of AccessControlRecord)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Ruft alle zugriffssteuerungsdatensätze in einem Manager ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;ListByManagerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle zugriffssteuerungsdatensätze in einem Manager ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>