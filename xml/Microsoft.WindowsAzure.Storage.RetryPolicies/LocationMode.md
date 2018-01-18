<Type Name="LocationMode" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode">
  <TypeSignature Language="C#" Value="public enum LocationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LocationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum LocationMode" />
  <TypeSignature Language="F#" Value="type LocationMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="76e47-101">Gibt den Modus des Speicherorts, an welcher Stelle die Anforderung erhalten soll.</span><span class="sxs-lookup"><span data-stu-id="76e47-101">Specifies the location mode to indicate which location should receive the request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PrimaryOnly">
      <MemberSignature Language="C#" Value="PrimaryOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode PrimaryOnly = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryOnly" />
      <MemberSignature Language="VB.NET" Value="PrimaryOnly" />
      <MemberSignature Language="F#" Value="PrimaryOnly = 0" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76e47-102">Anforderungen werden stets an den primären Speicherort gesendet.</span><span class="sxs-lookup"><span data-stu-id="76e47-102">Requests are always sent to the primary location.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="76e47-103">Wenn dieser Wert für Anforderungen, die nur für einen sekundären Standort (z. B. GetServiceStats) funktionieren verwendet wird, schlägt die Anforderung des Clients fehl.</span><span class="sxs-lookup"><span data-stu-id="76e47-103">If this value is used for requests that only work against a secondary location (GetServiceStats, for example), the request will fail in the client.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryThenSecondary">
      <MemberSignature Language="C#" Value="PrimaryThenSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode PrimaryThenSecondary = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryThenSecondary" />
      <MemberSignature Language="VB.NET" Value="PrimaryThenSecondary" />
      <MemberSignature Language="F#" Value="PrimaryThenSecondary = 1" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.PrimaryThenSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76e47-104">Anforderungen werden stets zuerst an den primären Speicherort gesendet.</span><span class="sxs-lookup"><span data-stu-id="76e47-104">Requests are always sent to the primary location first.</span></span> <span data-ttu-id="76e47-105">Wenn eine Anforderung fehlschlägt, wird sie an den sekundären Standort gesendet.</span><span class="sxs-lookup"><span data-stu-id="76e47-105">If a request fails, it is sent to the secondary location.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="76e47-106">Wenn dieser Wert für Anforderungen, die nur für einen Standort gültig sind verwendet wird, wird der Client nur den zulässigen Speicherort abzielen.</span><span class="sxs-lookup"><span data-stu-id="76e47-106">If this value is used for requests that are only valid against one location, the client will only target the allowed location.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryOnly">
      <MemberSignature Language="C#" Value="SecondaryOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode SecondaryOnly = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryOnly" />
      <MemberSignature Language="VB.NET" Value="SecondaryOnly" />
      <MemberSignature Language="F#" Value="SecondaryOnly = 2" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76e47-107">Anforderungen werden stets an den sekundären Speicherort gesendet.</span><span class="sxs-lookup"><span data-stu-id="76e47-107">Requests are always sent to the secondary location.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="76e47-108">Wenn dieser Wert wird für Anforderungen verwendet, die nur für einen primären Standort funktionieren (erstellen, ändern und Löschen von APIs), die Anforderung schlägt fehl, auf dem Client.</span><span class="sxs-lookup"><span data-stu-id="76e47-108">If this value is used for requests that only work against a primary location (create, modify, and delete APIs), the request will fail in the client.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryThenPrimary">
      <MemberSignature Language="C#" Value="SecondaryThenPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode SecondaryThenPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryThenPrimary" />
      <MemberSignature Language="VB.NET" Value="SecondaryThenPrimary" />
      <MemberSignature Language="F#" Value="SecondaryThenPrimary = 3" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode.SecondaryThenPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="76e47-109">Anforderungen werden stets zuerst an den sekundären Speicherort gesendet.</span><span class="sxs-lookup"><span data-stu-id="76e47-109">Requests are always sent to the secondary location first.</span></span> <span data-ttu-id="76e47-110">Wenn eine Anforderung fehlschlägt, wird er an den primären Speicherort gesendet.</span><span class="sxs-lookup"><span data-stu-id="76e47-110">If a request fails, it is sent to the primary location.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="76e47-111">Wenn dieser Wert für Anforderungen, die nur für einen Standort gültig sind verwendet wird, wird der Client nur den zulässigen Speicherort abzielen.</span><span class="sxs-lookup"><span data-stu-id="76e47-111">If this value is used for requests that are only valid against one location, the client will only target the allowed location.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>