<Type Name="ServiceKind" FullName="System.Fabric.Query.ServiceKind">
  <TypeSignature Language="C#" Value="public enum ServiceKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceKind" />
  <TypeSignature Language="F#" Value="type ServiceKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="d0acb-101">Gibt die Art des Diensts an.</span><span class="sxs-lookup"><span data-stu-id="d0acb-101">Specifies the service kind.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServiceKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d0acb-102">Ungültig</span><span class="sxs-lookup"><span data-stu-id="d0acb-102">Invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Stateful">
      <MemberSignature Language="C#" Value="Stateful" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceKind Stateful = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceKind.Stateful" />
      <MemberSignature Language="VB.NET" Value="Stateful" />
      <MemberSignature Language="F#" Value="Stateful = 2" Usage="System.Fabric.Query.ServiceKind.Stateful" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d0acb-103">Verwendet Service Fabric um den Status vollständig oder teilweise als hochverfügbar und zuverlässig zu machen.</span><span class="sxs-lookup"><span data-stu-id="d0acb-103">Uses Service Fabric to make its state or part of its state highly available and reliable.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Stateless">
      <MemberSignature Language="C#" Value="Stateless" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceKind Stateless = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceKind.Stateless" />
      <MemberSignature Language="VB.NET" Value="Stateless" />
      <MemberSignature Language="F#" Value="Stateless = 1" Usage="System.Fabric.Query.ServiceKind.Stateless" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d0acb-104">Service Fabric verwendet nicht den Zustand hochverfügbar oder zuverlässig vornehmen.</span><span class="sxs-lookup"><span data-stu-id="d0acb-104">Does not use Service Fabric to make its state highly available or reliable.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>