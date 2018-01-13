<Type Name="VirtualDiskOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualDiskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualDiskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualDiskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualDiskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreating (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Der Vorgang beginnen erstellen-Datenträger wird ein neues Volume erstellt.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreatingAsync (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Der Vorgang beginnen erstellen-Datenträger wird ein neues Volume erstellt.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeleting (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Instanz-Id des virtuellen Datenträgers gelöscht werden soll.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Das Löschen des Datenträgers beginnen-Vorgang löscht das angegebene Volume.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeletingAsync (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Instanz-Id des virtuellen Datenträgers gelöscht werden soll.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Das Löschen des Datenträgers beginnen-Vorgang löscht das angegebene Volume.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdating (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdating(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdating(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdating : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdating (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Datenträger-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Das Aktualisieren der Volume-Vorgang beginnen aktualisiert ein vorhandenes Volume an.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdatingAsync (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Datenträger-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Das Aktualisieren der Volume-Vorgang beginnen aktualisiert ein vorhandenes Volume an.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Create (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.CreateAsync (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Erstellungsvorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Delete (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Datenträger-id
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.DeleteAsync (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Datenträger-id
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByName">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse GetByName (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse GetByName(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByName(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetByName : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByName (operations, deviceId, diskName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Optional.
            </param>
        <param name="diskName">
            Optional.
            </param>
        <param name="customRequestHeaders">
            Optional.
            </param>
        <summary>To be added.</summary>
        <returns>
            Das Antwort-Modell für das Abrufen des virtuellen Datenträgers.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt; GetByNameAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt; GetByNameAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByNameAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetByNameAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByNameAsync (operations, deviceId, diskName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Optional.
            </param>
        <param name="diskName">
            Optional.
            </param>
        <param name="customRequestHeaders">
            Optional.
            </param>
        <summary>To be added.</summary>
        <returns>
            Das Antwort-Modell für das Abrufen des virtuellen Datenträgers.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.List (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Optional.
            </param>
        <param name="dataContainerId">
            Optional.
            </param>
        <param name="customRequestHeaders">
            Optional.
            </param>
        <summary>To be added.</summary>
        <returns>
            Das Antwort-Modell für die Liste der virtuellen Datenträger für einen angegebenen Container.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.ListAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Optional.
            </param>
        <param name="dataContainerId">
            Optional.
            </param>
        <param name="customRequestHeaders">
            Optional.
            </param>
        <summary>To be added.</summary>
        <returns>
            Das Antwort-Modell für die Liste der virtuellen Datenträger für einen angegebenen Container.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Update(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Update (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Datenträger-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.UpdateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.UpdateAsync (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.
            </param>
        <param name="deviceId">
            Erforderlich. Geräte-id
            </param>
        <param name="diskId">
            Erforderlich. Datenträger-id
            </param>
        <param name="diskDetails">
            Erforderlich. Parameter, die auf den Updatevorgang für die virtuelle Festplatte angegeben werden.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>