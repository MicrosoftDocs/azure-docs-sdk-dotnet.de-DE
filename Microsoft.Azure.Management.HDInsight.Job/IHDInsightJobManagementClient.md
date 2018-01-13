<Type Name="IHDInsightJobManagementClient" FullName="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient">
  <TypeSignature Language="C#" Value="public interface IHDInsightJobManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHDInsightJobManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHDInsightJobManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IHDInsightJobManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2f90f-101">Der HDInsight-Auftrags-Client verwaltet die Aufträge für HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="2f90f-101">The HDInsight job client manages jobs against HDInsight clusters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClusterDnsName">
      <MemberSignature Language="C#" Value="public string ClusterDnsName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterDnsName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.ClusterDnsName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ClusterDnsName : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.ClusterDnsName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f90f-102">Der Cluster DNS-Name für die ist die auftragsverwaltung ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="2f90f-102">The cluster dns name against which the job management is to be performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Hyak.Common.BasicAuthenticationCloudCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Hyak.Common.BasicAuthenticationCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As BasicAuthenticationCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Hyak.Common.BasicAuthenticationCloudCredentials with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Hyak.Common.BasicAuthenticationCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f90f-103">Standardauthentifizierungs-Anmeldeinformationen für die Auftragsübermittlung.</span><span class="sxs-lookup"><span data-stu-id="2f90f-103">Basic authentication credentials for job submission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagement">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Job.IJobOperations JobManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Job.IJobOperations JobManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.JobManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobManagement As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.JobManagement : Microsoft.Azure.Management.HDInsight.Job.IJobOperations" Usage="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.JobManagement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Job.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f90f-104">Vorgänge zum Verwalten von Aufträgen für HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="2f90f-104">Operations for managing jobs against HDInsight clusters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SdkUserAgent">
      <MemberSignature Language="C#" Value="public string SdkUserAgent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SdkUserAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.SdkUserAgent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SdkUserAgent As String" />
      <MemberSignature Language="F#" Value="member this.SdkUserAgent : string" Usage="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.SdkUserAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f90f-105">Text abruft oder festlegt der SDK-UserAgent der Benutzer-Agent-Header hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="2f90f-105">Gets or sets the SDK UserAgent text to be added to the user agent header.</span></span> <span data-ttu-id="2f90f-106">Dient zur weiteren verschiedenen SDK-Versionen zu unterscheiden.</span><span class="sxs-lookup"><span data-stu-id="2f90f-106">This is used to further differentiate various SDK versions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentSuffix">
      <MemberSignature Language="C#" Value="public string UserAgentSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.UserAgentSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentSuffix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentSuffix : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.UserAgentSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f90f-107">Ruft ab, oder legt ihn fest der zusätzlichen UserAgent Text ein, die Benutzer-Agent-Header hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="2f90f-107">Gets or sets the additional UserAgent text to be added to the user agent header.</span></span> <span data-ttu-id="2f90f-108">Dies wird verwendet, stärker unterscheiden-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="2f90f-108">This is used to further differentiate using applications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.UserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string" Usage="Microsoft.Azure.Management.HDInsight.Job.IHDInsightJobManagementClient.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight.Job</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f90f-109">Der Benutzername aus dem Benutzernamen des BasicAuthenticationCloudCredentials in Kleinbuchstaben angegeben, die für die Ausführung des Auftrags verwendet.</span><span class="sxs-lookup"><span data-stu-id="2f90f-109">The user name from Username of BasicAuthenticationCloudCredentials in lower case used for running job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>