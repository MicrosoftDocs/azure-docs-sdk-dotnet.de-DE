<Type Name="DeviceJobStatistics" FullName="Microsoft.Azure.Devices.DeviceJobStatistics">
  <TypeSignature Language="C#" Value="public class DeviceJobStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeviceJobStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.DeviceJobStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceJobStatistics" />
  <TypeSignature Language="F#" Value="type DeviceJobStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3d226-101">Der Auftrag zählt z. B. Anzahl der Geräte erfolgreich/Fehler</span><span class="sxs-lookup"><span data-stu-id="3d226-101">The job counts, e.g., number of failed/succeeded devices</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceJobStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.DeviceJobStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceCount">
      <MemberSignature Language="C#" Value="public int DeviceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeviceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceJobStatistics.DeviceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeviceCount : int with get, set" Usage="Microsoft.Azure.Devices.DeviceJobStatistics.DeviceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d226-102">Anzahl der Geräte im Auftrag</span><span class="sxs-lookup"><span data-stu-id="3d226-102">Number of devices in the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedCount">
      <MemberSignature Language="C#" Value="public int FailedCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FailedCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceJobStatistics.FailedCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FailedCount : int with get, set" Usage="Microsoft.Azure.Devices.DeviceJobStatistics.FailedCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failedCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d226-103">die Anzahl der fehlerhaften Aufträge</span><span class="sxs-lookup"><span data-stu-id="3d226-103">The number of failed jobs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingCount">
      <MemberSignature Language="C#" Value="public int PendingCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PendingCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceJobStatistics.PendingCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PendingCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PendingCount : int with get, set" Usage="Microsoft.Azure.Devices.DeviceJobStatistics.PendingCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pendingCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d226-104">Die Anzahl der ausstehenden Aufträge (geplant)</span><span class="sxs-lookup"><span data-stu-id="3d226-104">The number of pending (scheduled) jobs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningCount">
      <MemberSignature Language="C#" Value="public int RunningCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RunningCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceJobStatistics.RunningCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RunningCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RunningCount : int with get, set" Usage="Microsoft.Azure.Devices.DeviceJobStatistics.RunningCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d226-105">die Anzahl der ausgeführten Aufträge</span><span class="sxs-lookup"><span data-stu-id="3d226-105">The number of running jobs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SucceededCount">
      <MemberSignature Language="C#" Value="public int SucceededCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SucceededCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.DeviceJobStatistics.SucceededCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SucceededCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SucceededCount : int with get, set" Usage="Microsoft.Azure.Devices.DeviceJobStatistics.SucceededCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="succeededCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d226-106">Die Anzahl der Successed Aufträge</span><span class="sxs-lookup"><span data-stu-id="3d226-106">The number of Successed jobs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>