<Type Name="CloneVolumeOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CloneVolumeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloneVolumeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloneVolumeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CloneVolumeOperationsExtensions = class" />
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
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger (this Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger(class Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.Trigger(Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.Trigger (operations, sourceDeviceId, triggerCloneRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" RefType="this" />
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="triggerCloneRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations.
            </param>
        <param name="sourceDeviceId">
            Erforderlich. Der Bezeichner für das Quellgerät aus der Klon wird ausgelöst werden soll
            </param>
        <param name="triggerCloneRequest">
            Erforderlich. Die Parameter für den Klonvorgang erforderlich
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Der benutzerdefinierte Client verwenden, muss Anforderungsheader
            </param>
        <summary>
            Klonen einer backup-Element.
            </summary>
        <returns>
            Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (this Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(class Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.TriggerAsync(Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.TriggerAsync (operations, sourceDeviceId, triggerCloneRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" RefType="this" />
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="triggerCloneRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations.
            </param>
        <param name="sourceDeviceId">
            Erforderlich. Der Bezeichner für das Quellgerät aus der Klon wird ausgelöst werden soll
            </param>
        <param name="triggerCloneRequest">
            Erforderlich. Die Parameter für den Klonvorgang erforderlich
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Der benutzerdefinierte Client verwenden, muss Anforderungsheader
            </param>
        <summary>
            Klonen einer backup-Element.
            </summary>
        <returns>
            Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>