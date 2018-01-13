<Type Name="BackupsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupsOperationsExtensions = class" />
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
            Erweiterungsmethoden für BackupsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginClone">
      <MemberSignature Language="C#" Value="public static void BeginClone (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginClone(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginClone(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginClone (operations As IBackupsOperations, deviceName As String, backupName As String, backupElementName As String, parameters As CloneRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginClone : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginClone (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
            </param>
        <param name="backupElementName">
            Der Name des backup-Element.
            </param>
        <param name="parameters">
            Das Klon-Request-Objekt.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Klont die backup-Element als ein neues Volume an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCloneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginCloneAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginCloneAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginCloneAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCloneAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginCloneAsync (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;BeginCloneAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
            </param>
        <param name="backupElementName">
            Der Name des backup-Element.
            </param>
        <param name="parameters">
            Das Klon-Request-Objekt.
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
            Klont die backup-Element als ein neues Volume an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDelete (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Löscht die Sicherung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDeleteAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
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
            Löscht die Sicherung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestore">
      <MemberSignature Language="C#" Value="public static void BeginRestore (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRestore(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestore(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRestore (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRestore : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestore (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name des Sicherungssatzes
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Stellt die Sicherung auf dem Gerät.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRestoreAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRestoreAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestoreAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestoreAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestoreAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;BeginRestoreAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name des Sicherungssatzes
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
            Stellt die Sicherung auf dem Gerät.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public static void Clone (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Clone(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Clone(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Clone (operations As IBackupsOperations, deviceName As String, backupName As String, backupElementName As String, parameters As CloneRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Clone : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Clone (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
            </param>
        <param name="backupElementName">
            Der Name des backup-Element.
            </param>
        <param name="parameters">
            Das Klon-Request-Objekt.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Klont die backup-Element als ein neues Volume an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CloneAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CloneAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.CloneAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CloneAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.CloneAsync (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;CloneAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
            </param>
        <param name="backupElementName">
            Der Name des backup-Element.
            </param>
        <param name="parameters">
            Das Klon-Request-Objekt.
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
            Klont die backup-Element als ein neues Volume an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Delete (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Löscht die Sicherung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.DeleteAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name der Sicherungskopie.
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
            Löscht die Sicherung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IBackupsOperations, deviceName As String, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of BackupFilter) = null) As IPage(Of Backup)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt;" />
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
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <summary>
            Ruft alle Sicherungen in einem Gerät ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt;" />
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
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle Sicherungen in einem Gerät ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDeviceNext (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDeviceNext(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNext(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDeviceNext (operations As IBackupsOperations, nextPageLink As String) As IPage(Of Backup)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceNext : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft alle Sicherungen in einem Gerät ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceNextAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceNextAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNextAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceNextAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;ListByDeviceNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle Sicherungen in einem Gerät ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public static void Restore (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Restore(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Restore(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Restore (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Restore : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Restore (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name des Sicherungssatzes
            </param>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="managerName">
            Den Namen des Managers
            </param>
        <summary>
            Stellt die Sicherung auf dem Gerät.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RestoreAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RestoreAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.RestoreAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.RestoreAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;RestoreAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
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
        <param name="backupName">
            Der Name des Sicherungssatzes
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
            Stellt die Sicherung auf dem Gerät.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>