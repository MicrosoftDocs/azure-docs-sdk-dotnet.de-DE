<Type Name="ComposeDeploymentStatusResultItem" FullName="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentStatusResultItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentStatusResultItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentStatusResultItem" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatusResultItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="2154b-101">Beschreibt verfassen Status Ergebnis Bereitstellungselement die durch Bereitstellungsname, Anwendungsname, Bereitstellungsstatus verfassen und Statusdetails gekennzeichnet sind.</span><span class="sxs-lookup"><span data-stu-id="2154b-101">Describes a compose deployment status result item which is characterized by deployment name, application name, compose deployment status , and status details.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2154b-102">Ruft den Namen der Anwendung als einen URI ab.</span><span class="sxs-lookup"><span data-stu-id="2154b-102">Gets the name of the application as a URI.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2154b-103">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="2154b-103">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeDeploymentStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus ComposeDeploymentStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus ComposeDeploymentStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeDeploymentStatus As ComposeDeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.ComposeDeploymentStatus : Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2154b-104">Ruft den Status der Bereitstellung als Compose <see cref="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />.</span><span class="sxs-lookup"><span data-stu-id="2154b-104">Gets the status of the compose deployment as <see cref="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2154b-105">Der Status der Bereitstellung verfassen.</span><span class="sxs-lookup"><span data-stu-id="2154b-105">The status of the compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.DeploymentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2154b-106">Ruft den Namen der Bereitstellung verfassen.</span><span class="sxs-lookup"><span data-stu-id="2154b-106">Gets the name of the compose deployment.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2154b-107">Der Name der Bereitstellung verfassen.</span><span class="sxs-lookup"><span data-stu-id="2154b-107">The name of the compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Fabric.Common.Serialization.JsonCustomization(IsDefaultValueIgnored=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2154b-108">Ruft die Statusdetails verfassen Bereitstellung einschließlich der Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="2154b-108">Gets the status details of compose deployment including failure message.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="2154b-109">Die Statusdetails bilden, Bereitstellung, einschließlich der Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="2154b-109">The status details of compose deployment including failure message.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>