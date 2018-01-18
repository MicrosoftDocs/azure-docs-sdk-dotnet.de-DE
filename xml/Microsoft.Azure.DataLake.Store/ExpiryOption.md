<Type Name="ExpiryOption" FullName="Microsoft.Azure.DataLake.Store.ExpiryOption">
  <TypeSignature Language="C#" Value="public enum ExpiryOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ExpiryOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.ExpiryOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ExpiryOption" />
  <TypeSignature Language="F#" Value="type ExpiryOption = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="72e10-101">Verschiedene Typen von Ablaufoptionen</span><span class="sxs-lookup"><span data-stu-id="72e10-101">Different types of expiry options</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Absolute">
      <MemberSignature Language="C#" Value="Absolute" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.ExpiryOption Absolute = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.ExpiryOption.Absolute" />
      <MemberSignature Language="VB.NET" Value="Absolute" />
      <MemberSignature Language="F#" Value="Absolute = 3" Usage="Microsoft.Azure.DataLake.Store.ExpiryOption.Absolute" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.ExpiryOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="72e10-102">ExpiryTime ist die tatsächliche Zeit</span><span class="sxs-lookup"><span data-stu-id="72e10-102">ExpiryTime is the actual time</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NeverExpire">
      <MemberSignature Language="C#" Value="NeverExpire" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.ExpiryOption NeverExpire = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.ExpiryOption.NeverExpire" />
      <MemberSignature Language="VB.NET" Value="NeverExpire" />
      <MemberSignature Language="F#" Value="NeverExpire = 0" Usage="Microsoft.Azure.DataLake.Store.ExpiryOption.NeverExpire" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.ExpiryOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="72e10-103">Datei abläuft nicht.</span><span class="sxs-lookup"><span data-stu-id="72e10-103">File will never expire.</span></span> <span data-ttu-id="72e10-104">ExpiryTime wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="72e10-104">ExpiryTime is ignored.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RelativeToCreationDate">
      <MemberSignature Language="C#" Value="RelativeToCreationDate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.ExpiryOption RelativeToCreationDate = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.ExpiryOption.RelativeToCreationDate" />
      <MemberSignature Language="VB.NET" Value="RelativeToCreationDate" />
      <MemberSignature Language="F#" Value="RelativeToCreationDate = 2" Usage="Microsoft.Azure.DataLake.Store.ExpiryOption.RelativeToCreationDate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.ExpiryOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="72e10-105">ExpiryTime ist zum Zeitpunkt Erstellung hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="72e10-105">ExpiryTime is added to the creation time</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RelativeToNow">
      <MemberSignature Language="C#" Value="RelativeToNow" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.ExpiryOption RelativeToNow = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.ExpiryOption.RelativeToNow" />
      <MemberSignature Language="VB.NET" Value="RelativeToNow" />
      <MemberSignature Language="F#" Value="RelativeToNow = 1" Usage="Microsoft.Azure.DataLake.Store.ExpiryOption.RelativeToNow" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.ExpiryOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="72e10-106">ExpiryTime ist bis zum aktuellen Zeitpunkt hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="72e10-106">ExpiryTime is added to the current time</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>