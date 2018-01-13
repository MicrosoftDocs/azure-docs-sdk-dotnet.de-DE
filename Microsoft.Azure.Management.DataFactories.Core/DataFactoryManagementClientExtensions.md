<Type Name="DataFactoryManagementClientExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class DataFactoryManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataFactoryManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataFactoryManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type DataFactoryManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetLongRunningOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse GetLongRunningOperationStatus (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse GetLongRunningOperationStatus(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatus(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLongRunningOperationStatus (operations As IDataFactoryManagementClient, operationStatusLink As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member GetLongRunningOperationStatus : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.
            </param>
        <param name="operationStatusLink">
            Erforderlich. Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.
            </param>
        <summary>
            Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück. Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLongRunningOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLongRunningOperationStatusAsync (operations As IDataFactoryManagementClient, operationStatusLink As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member GetLongRunningOperationStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.
            </param>
        <param name="operationStatusLink">
            Erforderlich. Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.
            </param>
        <summary>
            Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück. Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>