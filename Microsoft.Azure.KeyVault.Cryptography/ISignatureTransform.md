<Type Name="ISignatureTransform" FullName="Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform">
  <TypeSignature Language="C#" Value="public interface ISignatureTransform" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISignatureTransform" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISignatureTransform" />
  <TypeSignature Language="F#" Value="type ISignatureTransform = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f43e8-101">Abstrakte Signatur-Transformation.</span><span class="sxs-lookup"><span data-stu-id="f43e8-101">Abstract signature transform.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="public byte[] Sign (byte[] digest);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] Sign(unsigned int8[] digest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform.Sign(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function Sign (digest As Byte()) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member Sign : byte[] -&gt; byte[]" Usage="iSignatureTransform.Sign digest" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="digest"><span data-ttu-id="f43e8-102">Der Message-Digest.</span><span class="sxs-lookup"><span data-stu-id="f43e8-102">The message digest.</span></span></param>
        <summary>
            <span data-ttu-id="f43e8-103">Signiert die angegebene Digestwert an.</span><span class="sxs-lookup"><span data-stu-id="f43e8-103">Signs the supplied digest value.</span></span>
            </summary>
        <returns><span data-ttu-id="f43e8-104">Die Signaturwert.</span><span class="sxs-lookup"><span data-stu-id="f43e8-104">The signature value.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public bool Verify (byte[] digest, byte[] signature);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Verify(unsigned int8[] digest, unsigned int8[] signature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform.Verify(System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function Verify (digest As Byte(), signature As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Verify : byte[] * byte[] -&gt; bool" Usage="iSignatureTransform.Verify (digest, signature)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="digest"><span data-ttu-id="f43e8-105">Der Message-Digest.</span><span class="sxs-lookup"><span data-stu-id="f43e8-105">The message digest.</span></span></param>
        <param name="signature"><span data-ttu-id="f43e8-106">Die zu überprüfende Signatur.</span><span class="sxs-lookup"><span data-stu-id="f43e8-106">The signature to be verified.</span></span></param>
        <summary>
            <span data-ttu-id="f43e8-107">Stellt sicher, dass die angegebene Signatur mit der angegebenen Message Digest entspricht.</span><span class="sxs-lookup"><span data-stu-id="f43e8-107">Verifies that the supplied signature corresponds with the supplied message digest.</span></span>
            </summary>
        <returns><span data-ttu-id="f43e8-108">"true", wenn die Signatur gültig ist.</span><span class="sxs-lookup"><span data-stu-id="f43e8-108">true if the signature is valid.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>