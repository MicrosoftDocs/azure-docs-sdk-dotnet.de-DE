<Type Name="DeviceJobOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceJobOperationsExtensions = class" />
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
    <Member MemberName="BeginUpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.
            </param>
        <param name="deviceId">
            Erforderlich. ID des Geräts
            </param>
        <param name="jobId">
            Erforderlich. ID des Auftrags zu aktualisieren
            </param>
        <param name="updateRequest">
            Erforderlich. Anfordern von Daten, die auszuführende Aktion enthält
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Beginnen Sie die asynchrone Aufgabe, um einen Auftrag Gerät zu aktualisieren.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.
            </param>
        <param name="deviceId">
            Erforderlich. ID des Geräts
            </param>
        <param name="jobId">
            Erforderlich. ID des Auftrags zu aktualisieren
            </param>
        <param name="updateRequest">
            Erforderlich. Anfordern von Daten, die auszuführende Aktion enthält
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Beginnen Sie die asynchrone Aufgabe, um einen Auftrag Gerät zu aktualisieren.
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.
            </param>
        <param name="deviceId">
            Optional. Geräte-Id des Geräts von Aufträgen
            </param>
        <param name="jobType">
            Optional. Typ des deviceJob
            </param>
        <param name="jobStatus">
            Optional. Status des Auftrags
            </param>
        <param name="jobId">
            Optional. ID des Auftrags
            </param>
        <param name="startTime">
            Optional. Startzeit des Auftrags, im ISO 8601-Format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '
            </param>
        <param name="endTime">
            Optional. Endzeit der Auftrag, der im ISO 8601-format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '
            </param>
        <param name="skip">
            Erforderlich. Paginierung-Parameter. Die Anzahl der zu überspringenden Einträge, d. h. der Index des ersten Eintrags zurückgegeben werden
            </param>
        <param name="top">
            Erforderlich. Paginierung-Parameter. Die Anzahl von Einträgen zurückgegeben wird, nachdem die 'Skip' Anzahl von Einträgen übersprungen wird
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Antwort-Modell abrufen Abfrage für einen Auftrag Gerät
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.
            </param>
        <param name="deviceId">
            Optional. Geräte-Id des Geräts von Aufträgen
            </param>
        <param name="jobType">
            Optional. Typ des deviceJob
            </param>
        <param name="jobStatus">
            Optional. Status des Auftrags
            </param>
        <param name="jobId">
            Optional. ID des Auftrags
            </param>
        <param name="startTime">
            Optional. Startzeit des Auftrags, im ISO 8601-Format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '
            </param>
        <param name="endTime">
            Optional. Endzeit der Auftrag, der im ISO 8601-format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '
            </param>
        <param name="skip">
            Erforderlich. Paginierung-Parameter. Die Anzahl der zu überspringenden Einträge, d. h. der Index des ersten Eintrags zurückgegeben werden
            </param>
        <param name="top">
            Erforderlich. Paginierung-Parameter. Die Anzahl von Einträgen zurückgegeben wird, nachdem die 'Skip' Anzahl von Einträgen übersprungen wird
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Antwort-Modell abrufen Abfrage für einen Auftrag Gerät
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.
            </param>
        <param name="deviceId">
            Erforderlich. ID des Geräts
            </param>
        <param name="jobId">
            Erforderlich. ID des Auftrags zu aktualisieren
            </param>
        <param name="updateRequest">
            Erforderlich. Anfordern von Daten, die auszuführende Aktion enthält
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Aktualisieren eines Auftrags Gerät
            </summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.
            </param>
        <param name="deviceId">
            Erforderlich. ID des Geräts
            </param>
        <param name="jobId">
            Erforderlich. ID des Auftrags zu aktualisieren
            </param>
        <param name="updateRequest">
            Erforderlich. Anfordern von Daten, die auszuführende Aktion enthält
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>
            Aktualisieren eines Auftrags Gerät
            </summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>