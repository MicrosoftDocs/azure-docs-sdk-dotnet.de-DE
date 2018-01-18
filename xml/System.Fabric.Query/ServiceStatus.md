<Type Name="ServiceStatus" FullName="System.Fabric.Query.ServiceStatus">
  <TypeSignature Language="C#" Value="public enum ServiceStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceStatus" />
  <TypeSignature Language="F#" Value="type ServiceStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="d93b9-101">Stellt den Status eines Diensts, der durch den Aufruf abgerufen <see cref="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri)" />.</span><span class="sxs-lookup"><span data-stu-id="d93b9-101">Represents the status of a service retrieved by calling <see cref="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceStatus Active = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceStatus.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 1" Usage="System.Fabric.Query.ServiceStatus.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d93b9-102">Der Dienst wurde erfolgreich erstellt.</span><span class="sxs-lookup"><span data-stu-id="d93b9-102">The service has been successfully created.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceStatus Creating = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceStatus.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 4" Usage="System.Fabric.Query.ServiceStatus.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d93b9-103">Der Dienst wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="d93b9-103">The service is being created.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceStatus Deleting = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceStatus.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 3" Usage="System.Fabric.Query.ServiceStatus.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d93b9-104">Der Dienst wird gelöscht.</span><span class="sxs-lookup"><span data-stu-id="d93b9-104">The service is being deleted.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceStatus Failed = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceStatus.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 5" Usage="System.Fabric.Query.ServiceStatus.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d93b9-105">Erstellen oder Löschen von wurde aufgrund von permanenten Fehlern beendet.</span><span class="sxs-lookup"><span data-stu-id="d93b9-105">Creation or deletion was terminated due to persistent failures.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceStatus Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceStatus.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="System.Fabric.Query.ServiceStatus.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d93b9-106">Der Dienststatus wird noch nicht bekannt.</span><span class="sxs-lookup"><span data-stu-id="d93b9-106">The service status is not yet known.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Upgrading">
      <MemberSignature Language="C#" Value="Upgrading" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceStatus Upgrading = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceStatus.Upgrading" />
      <MemberSignature Language="VB.NET" Value="Upgrading" />
      <MemberSignature Language="F#" Value="Upgrading = 2" Usage="System.Fabric.Query.ServiceStatus.Upgrading" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d93b9-107">Der Dienst wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="d93b9-107">The service is being upgraded.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>