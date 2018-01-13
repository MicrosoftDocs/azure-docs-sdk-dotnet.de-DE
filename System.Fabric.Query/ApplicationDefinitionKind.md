<Type Name="ApplicationDefinitionKind" FullName="System.Fabric.Query.ApplicationDefinitionKind">
  <TypeSignature Language="C#" Value="public enum ApplicationDefinitionKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationDefinitionKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationDefinitionKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationDefinitionKind" />
  <TypeSignature Language="F#" Value="type ApplicationDefinitionKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="edfab-101">Gibt die Art der Anwendung-Definition.</span><span class="sxs-lookup"><span data-stu-id="edfab-101">Specifies the application definition kind.</span></span></para>
      <para><span data-ttu-id="edfab-102">Gibt den Mechanismus der Benutzer verwendet, um eine Service Fabric-Anwendung zu definieren.</span><span class="sxs-lookup"><span data-stu-id="edfab-102">Specifies the mechanism the user used to define a Service Fabric application.</span></span> <span data-ttu-id="edfab-103">Service Fabric können Benutzer die Anwendung mit einem Service Fabric-anwendungsbeschreibung beschreiben oder Verfassen mithilfe von Dateien.</span><span class="sxs-lookup"><span data-stu-id="edfab-103">Service Fabric allows users to describe the application by using a Service Fabric application description or by using compose file(s).</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Compose">
      <MemberSignature Language="C#" Value="Compose" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ApplicationDefinitionKind Compose = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ApplicationDefinitionKind.Compose" />
      <MemberSignature Language="VB.NET" Value="Compose" />
      <MemberSignature Language="F#" Value="Compose = 1" Usage="System.Fabric.Query.ApplicationDefinitionKind.Compose" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="edfab-104">Gibt an, dass die Anwendung definiert ist von Dateien zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="edfab-104">Indicates that the application is defined by compose file(s).</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ApplicationDefinitionKind Invalid = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ApplicationDefinitionKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 65535" Usage="System.Fabric.Query.ApplicationDefinitionKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="edfab-105">Ungültig</span><span class="sxs-lookup"><span data-stu-id="edfab-105">Invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceFabricApplicationDescription">
      <MemberSignature Language="C#" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ApplicationDefinitionKind ServiceFabricApplicationDescription = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ApplicationDefinitionKind.ServiceFabricApplicationDescription" />
      <MemberSignature Language="VB.NET" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="F#" Value="ServiceFabricApplicationDescription = 0" Usage="System.Fabric.Query.ApplicationDefinitionKind.ServiceFabricApplicationDescription" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="edfab-106">Gibt an, dass von die Anwendung definiert wird <see cref="T:System.Fabric.Description.ApplicationDescription" />.</span><span class="sxs-lookup"><span data-stu-id="edfab-106">Indicates that the application is defined by <see cref="T:System.Fabric.Description.ApplicationDescription" />.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>