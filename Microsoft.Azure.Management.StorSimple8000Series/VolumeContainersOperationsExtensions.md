<Type Name="VolumeContainersOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VolumeContainersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VolumeContainersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VolumeContainersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VolumeContainersOperationsExtensions = class" />
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
            Erweiterungsmethoden für VolumeContainersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, parameters As VolumeContainer, resourceGroupName As String, managerName As String) As VolumeContainer" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="parameters">
            Der volumecontainer hinzugefügt oder aktualisiert werden soll.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Erstellt oder aktualisiert die Volume-Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="parameters">
            Der volumecontainer hinzugefügt oder aktualisiert werden soll.
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
            Erstellt oder aktualisiert die Volume-Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDelete (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Löscht den volumecontainer.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDeleteAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
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
            Löscht den volumecontainer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, parameters As VolumeContainer, resourceGroupName As String, managerName As String) As VolumeContainer" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdate (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="parameters">
            Der volumecontainer hinzugefügt oder aktualisiert werden soll.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Erstellt oder aktualisiert die Volume-Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="parameters">
            Der volumecontainer hinzugefügt oder aktualisiert werden soll.
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
            Erstellt oder aktualisiert die Volume-Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Delete (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Löscht den volumecontainer.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.DeleteAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
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
            Löscht den volumecontainer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer Get (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer Get(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As VolumeContainer" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Get (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Ruft die Eigenschaften des angegebenen Volume-Container Namens ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.GetAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
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
            Ruft die Eigenschaften des angegebenen Volume-Container Namens ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IVolumeContainersOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of VolumeContainer)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Ruft alle volumecontainer in einem Gerät ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
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
            Ruft alle volumecontainer in einem Gerät ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinition (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Ruft die metrikdefinitionen für den angegebenen Volume-Container ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinitionAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
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
            Ruft die metrikdefinitionen für den angegebenen Volume-Container ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IVolumeContainersOperations, odataQuery As ODataQuery(Of MetricFilter), deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetrics (operations, odataQuery, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Ruft die Metriken für den angegebenen Volume-Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricsAsync (operations, odataQuery, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;ListMetricsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="deviceName">
            Der Name des Laufwerks
            </param>
        <param name="volumeContainerName">
            Der Name des Volume-Container.
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
            Ruft die Metriken für den angegebenen Volume-Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>