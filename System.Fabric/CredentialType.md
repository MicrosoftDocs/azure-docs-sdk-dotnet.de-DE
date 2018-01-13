<Type Name="CredentialType" FullName="System.Fabric.CredentialType">
  <TypeSignature Language="C#" Value="public enum CredentialType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CredentialType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CredentialType" />
  <TypeSignature Language="VB.NET" Value="Public Enum CredentialType" />
  <TypeSignature Language="F#" Value="type CredentialType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="cb926-101">Definiert die gültigen Arten von Sicherheitsanmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="cb926-101">Defines the valid kinds of security credentials.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="Claims" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType Claims = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.Claims" />
      <MemberSignature Language="VB.NET" Value="Claims" />
      <MemberSignature Language="F#" Value="Claims = 3" Usage="System.Fabric.CredentialType.Claims" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cb926-102">Das Forderungstoken, das vom STS (Sicherheitstokendienst) bezogen.</span><span class="sxs-lookup"><span data-stu-id="cb926-102">The claims token acquired from STS (security token service).</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.CredentialType.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cb926-103">Keine definierte Anmeldeinformationen (Standard).</span><span class="sxs-lookup"><span data-stu-id="cb926-103">No credential defined (default).</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Windows">
      <MemberSignature Language="C#" Value="Windows" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType Windows = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.Windows" />
      <MemberSignature Language="VB.NET" Value="Windows" />
      <MemberSignature Language="F#" Value="Windows = 2" Usage="System.Fabric.CredentialType.Windows" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cb926-104">Die Anmeldeinformationen für den active Directory-Domäne.</span><span class="sxs-lookup"><span data-stu-id="cb926-104">The active directory domain credential.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="X509">
      <MemberSignature Language="C#" Value="X509" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType X509 = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.X509" />
      <MemberSignature Language="VB.NET" Value="X509" />
      <MemberSignature Language="F#" Value="X509 = 1" Usage="System.Fabric.CredentialType.X509" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="cb926-105">Die X509 Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="cb926-105">The X509 certificate.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>