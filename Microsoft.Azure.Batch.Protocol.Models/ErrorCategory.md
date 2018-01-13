<Type Name="ErrorCategory" FullName="Microsoft.Azure.Batch.Protocol.Models.ErrorCategory">
  <TypeSignature Language="C#" Value="public enum ErrorCategory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ErrorCategory extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ErrorCategory" />
  <TypeSignature Language="VB.NET" Value="Public Enum ErrorCategory" />
  <TypeSignature Language="F#" Value="type ErrorCategory = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ddfc1-101">Definiert Werte für ErrorCategory an.</span><span class="sxs-lookup"><span data-stu-id="ddfc1-101">Defines values for ErrorCategory.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ServerError">
      <MemberSignature Language="C#" Value="ServerError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory ServerError = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ErrorCategory.ServerError" />
      <MemberSignature Language="VB.NET" Value="ServerError" />
      <MemberSignature Language="F#" Value="ServerError = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ErrorCategory.ServerError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="servererror")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorCategory</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ddfc1-102">Der Fehler wird aufgrund eines internen Server Problems.</span><span class="sxs-lookup"><span data-stu-id="ddfc1-102">The error is due to an internal server issue.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UserError">
      <MemberSignature Language="C#" Value="UserError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ErrorCategory UserError = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ErrorCategory.UserError" />
      <MemberSignature Language="VB.NET" Value="UserError" />
      <MemberSignature Language="F#" Value="UserError = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ErrorCategory.UserError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="usererror")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorCategory</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ddfc1-103">Der Fehler wird aufgrund eines Problems mit Benutzer, z. B. Fehlkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="ddfc1-103">The error is due to a user issue, such as misconfiguration.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>