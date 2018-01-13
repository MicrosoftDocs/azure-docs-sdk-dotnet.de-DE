<Type Name="DataSourceFilter" FullName="Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter">
  <TypeSignature Language="C#" Value="public class DataSourceFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSourceFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSourceFilter" />
  <TypeSignature Language="F#" Value="type DataSourceFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="231e4-101">DataSource-Filter.</span><span class="sxs-lookup"><span data-stu-id="231e4-101">DataSource filter.</span></span> <span data-ttu-id="231e4-102">Jetzt, nur nach Art Filtern wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="231e4-102">Right now, only filter by kind is supported.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="231e4-103">Initialisiert eine neue Instanz der DataSourceFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="231e4-103">Initializes a new instance of the DataSourceFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceFilter (string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter : string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="231e4-104">Folgende Werte sind möglich: "AzureActivityLog", "ChangeTrackingPath", "ChangeTrackingDefaultPath", "ChangeTrackingDefaultRegistry", "ChangeTrackingCustomRegistry", "CustomLog", "CustomLogCollection", "GenericDataSource", "IISLogs", "LinuxPerformanceObject", "LinuxPerformanceCollection", "LinuxSyslog", "LinuxSyslogCollection", "WindowsEvent", "WindowsPerformanceCounter"</span><span class="sxs-lookup"><span data-stu-id="231e4-104">Possible values include: 'AzureActivityLog', 'ChangeTrackingPath', 'ChangeTrackingDefaultPath', 'ChangeTrackingDefaultRegistry', 'ChangeTrackingCustomRegistry', 'CustomLog', 'CustomLogCollection', 'GenericDataSource', 'IISLogs', 'LinuxPerformanceObject', 'LinuxPerformanceCollection', 'LinuxSyslog', 'LinuxSyslogCollection', 'WindowsEvent', 'WindowsPerformanceCounter'</span></span></param>
        <summary>
            <span data-ttu-id="231e4-105">Initialisiert eine neue Instanz der DataSourceFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="231e4-105">Initializes a new instance of the DataSourceFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="231e4-106">Ruft ab oder legt folgende Werte möglich sind: "AzureActivityLog" "ChangeTrackingPath" "ChangeTrackingDefaultPath" "ChangeTrackingDefaultRegistry" "ChangeTrackingCustomRegistry" "CustomLog" "CustomLogCollection", "GenericDataSource", " IISLogs', 'LinuxPerformanceObject', "LinuxPerformanceCollection", "LinuxSyslog", "LinuxSyslogCollection", "WindowsEvent", "WindowsPerformanceCounter"</span><span class="sxs-lookup"><span data-stu-id="231e4-106">Gets or sets possible values include: 'AzureActivityLog', 'ChangeTrackingPath', 'ChangeTrackingDefaultPath', 'ChangeTrackingDefaultRegistry', 'ChangeTrackingCustomRegistry', 'CustomLog', 'CustomLogCollection', 'GenericDataSource', 'IISLogs', 'LinuxPerformanceObject', 'LinuxPerformanceCollection', 'LinuxSyslog', 'LinuxSyslogCollection', 'WindowsEvent', 'WindowsPerformanceCounter'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>